# Puhguh submission

Team: **puhguh**. Submit this fork's URL: https://github.com/Xuanming-Guo/poker_bot

The required files are **model.py** and the actual binary **puhguh.pkl** at the root of main. Use both from the same revision. The source contains every team runtime class and precomputed table; the organizer's shared files are unchanged.

The selected verified baseline is ContextValueModel. It passed 32,000 official-worker hands with zero faults/timeouts, exact duplicate mirror ties, and 10,229 source/packed decisions without a mismatch. All 11 organizer Model/documentation tests and the official submit validator passed; regeneration produced identical pickle bytes. This establishes package validity, not tournament victory.

The latest organizer update supplied by the team specifies 800 physical hands in round one and 2,000 in round two, corresponding to 400 and 1,000 deals per seat rotation. The previous top-five qualification rule was not changed in that update. Stacks reset each hand: 500 chips, blinds 10/20, with 10 seconds per callback.

Normal setup and tests are in README.md. To regenerate and validate: `python -m submit --team puhguh`. Source/pickle checksums and validation counts are in PUHGUH_SUBMISSION_MANIFEST.json. No GPU, network or external data files are required at play time. Experiments remain separate until matched testing and package checks support an update.
