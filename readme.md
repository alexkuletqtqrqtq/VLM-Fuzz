
## ⚠️ Research Prototype
```
The project entered an active refactoring phase to improve code quality, modularity, documentation,
and usability. A cleaned version of the repository will be released soon.
```

[![arXiv](https://img.shields.io/badge/arXiv-2504.11675-b31b1b.svg)](https://arxiv.org/abs/2504.11675) 
## VLM-Fuzz: Vision Language Model Assisted Recursive Depth-first Search Exploration for Effective UI Testing of Android Apps

# How to run

set env variable "OPENAI_API_KEY" with your OPENAI API KEY
export OPENAI_API_KEY=you-key

- prepare the emulator and launch it
- run the script in ui_dumper directory and wait until it's ready
- run ./run.sh path/to/apk  if you have one emulator only. 

----

# Custom emulator/device port (multi emulator/device setting)

If you need to use custom emulator ports in multi emulator setting or custom budget, make sure to install the apk on the right emulator and run the following script specifying the right port and budget

python main.py [-h] -a APK [-p PORT] [-b BUDGET]

-a path/to/apk
-p emulator port if not default
-b budget in minutes, default is 60 mins
-h show help

<img src="net.everythingandroid.timer_test2.png" alt="transition example">

```bibtex
@article{demissie2026vlm,
  title={VLM-Fuzz: Vision language model assisted recursive depth-first search exploration for effective GUI testing of android apps},
  author={Demissie, Biniam Fisseha and Tun, Yan Naing and Shar, Lwin Khin and Ceccato, Mariano},
  journal={Empirical Software Engineering},
  volume={31},
  number={3},
  pages={76},
  year={2026},
  publisher={Springer}
}
```


