# Singapore Werkz Photography 2021
code to scrap graduation photos of students from NUS

<p align="center">
  <img src="https://www.werkzgallery.com/images/logo-werkz.gif" width='400' height='100'/>
</p>

## Disclaimer
1. USE AT OWN DISCRETION
2. FOR EDUCATIONAL PURPOSES ONLY

## Requirements:
Software
1. [Python 3](https://www.python.org/ftp/python/3.8.5/python-3.8.5.exe)

Hardware
1. Laptop / Desktop (running windows or mac)

## Instructions:
1. Download repository as a zip folder
2. Unzip the folder
3. Run [getimages.py](https://github.com/hongyime/sgWerkzPhotography2021/blob/main/getimages.py) to find all possible photos (You'll need a list of possible NUSNET IDs first. Find them [here](https://github.com/hongyime/nusnet-id-code).)
4. Poke around and look at the other stuff uploaded

## License

Apache-2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

2026-09-12 maintenance: the LFS guard now checks out one commit because it scans the current index. Git scan errors fail the job instead of appearing to be a successful empty scan. The shared source change is verified in [sourcerepo PR #51](https://github.com/hongyime/sourcerepo/pull/51), with all ten Linux fixtures passing. Existing pointer rejection, opt-out behavior and action references are preserved. This workflow-only change leaves application code and data unchanged. Release requires passing hosted checks, followed by verification of the merged main workflow.
