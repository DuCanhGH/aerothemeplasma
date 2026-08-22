# Contributing

## Creating issues

Before making an issue, please take the time to look through already existing and closed issues on both the GitGud and GitHub repo, to prevent duplicate issues. If an issue becomes relevant again, feel free to make a post in the relevant issue thread and it'll be reopened.

Things that are helpful when writing an issue:

- Try to describe the problem as best as possible
- Is the issue consistently reproducible? If so, provide the steps to reproduce the issue
- If the problem is visual, try to record it or screenshot it
- Provide logs of `plasmashell`, `kwin_x11`, `kwin_wayland` etc. as the issue occurs. For more information regarding testing and logging, read [DOCUMENTATION.md](./DOCUMENTATION.md).
- Provide the following relevant specifications of your system:
    - Linux distribution, version and CPU architecture
    - Qt, KDE and KDE Frameworks versions
    - Display server (X11 and/or Wayland)
    - Monitor setup and monitor capabilities (Multimonitor, DPI, HDR, etc.)
    - GPU drivers
    
## Merge requests

Merge requests should only be done on the [GitGud](https://gitgud.io/aeroshell/atp/aerothemeplasma) repo as the GitHub repository is only a mirror.

## Usage of AI/LLMs 

(For context, the project has started receiving a small amount of AI-assisted merge requests, and as a result I imagine it'd be a good idea to actually take a stance on this.)

In general, the use of generative AI, LLMs, and other kinds of AI ('AI' will be used as a catch-all term moving forward) is highly discouraged within AeroShell and AeroThemePlasma. I personally do not use AI for writing code, creating assets, or for any other kind of assistance, including research, writing text, etc.

For merge requests, and submitted patches for AeroShell and AeroThemePlasma, the use of AI is highly discouraged, too. Some general guidelines:

- Please do not use AI to submit patches or merge requests. Merge requests that are obviously written with AI, with code that has obviously been created with AI (low quality, vibecoded, non-working, etc.) will be discarded.
- If you happen to submit a patch or create a merge request that utilizes AI in any capacity, please make sure to explicitly state that on submission.
- If you must use AI for whatever reason for code submissions, make sure to thoroughly tidy up the code, remove unnecessary comments, and properly test the code you're submitting for crashes and unintended behavior. Likewise, for MR descriptions, please write out the description by yourself.
- MRs containing AI-generated resources (images, audio, etc.) will be discarded.
