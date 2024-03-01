# How to make a change via git

Make sure you have installed [git bash](https://git-scm.com/downloads)

This guide will use the ***Linux*** command line, so if you use Windows, make sure to install [Windows Subsystem for Linux (WSL)](https://apps.microsoft.com/detail/9p9tqf7mrm4r?hl=en-au&gl=AU) and [Ubuntu](https://apps.microsoft.com/detail/9pdxgncfsczv?hl=en-au&gl=AU)

***NOTE:** If you are having problems, report and take pictures of the issue to our discord server.*

## Setup

1. Click on `Code` and then copy the HTTPS URL of the repository.

<img src="https://github.com/abyanmajid/info1111-project-cc18-2/assets/108279046/608dccda-721b-495d-a838-e2a3c4f4ba8a" width="300"> 

---

2. Open a Linux terminal/command line

<img src="https://github.com/abyanmajid/info1111-project-cc18-2/assets/108279046/b79f655f-fa56-49cc-9b91-2594cca418ad" width="400">

---

4. Navigate to your choice of directory (run `cd` and `ls` where necessary). See below for example.

<img src="https://github.com/abyanmajid/info1111-project-cc18-2/assets/108279046/7d332d14-cef1-480c-b195-b9c23c246bd5" width="400">

---

5. Clone this github repository to your chosen directory

```bash
git clone https://github.com/abyanmajid/info1111-task1-cc18-2.git
cd info1111-task1-cc18-2
```

Now you can make modifications to the `changes` directory. But before you edit anything, it is good practice to run
```bash
git pull
```
This will make sure that you update the clone you have made in your local device with the latest version of this github repository. Meaning, you'd have retrieved the latest changes made by others, before you start working.

*NOTE: **`changes/main.tex`** will be the main LaTeX file where we will be making our respective code changes to.*

---

## Updating this repository with the changes you made

Make sure you are in the right directory, i.e. if you run `ls`, you should see `changes`, `stable` and `README.md`

1. Run the following to tell git to keep track of all of the changes you have made so far in the current directory.

```bash
git add .
```

2. Run the following to save the changes you have made so far.

```bash
git commit -m "brief desc of your changes"
```

4. Run the following to push your changes to this repository (thereby replacing the current version with a new version containing your modifications).

```bash
git push -u origin main
```

*NOTE: You may occassionally be denied from running the above commands due to problems such as version clashes, etc. Usually, git will tell you the problem and the commands you need to do to resolve it. *

**You should run the commands as instructed by git. If you're stuck, report your issue to our Discord server.**
