# MultiagentRL_Simulations

Test

## Files Taxonomy

layout_ghostType_numGhosts_pacmanType_noise_commType_expNumber.txt

Where:

* layout: The layout type of the simulation
* ghostType: The type of the ghosts
* numGhosts: The number of ghosts from 1 to 4
* pacmanType: The type of the pacman
* noise: The amount of noise as a integer
* commType: The communication type
* expNumber: The number of the experiment from 01 to 30


## Directories Tree

```
├── classic_layout
│   ├── ghosts_2
│   │   ├── pacman_bfs
│   │   │   ├── communication_both
│   │   │   ├── communication_none
│   │   │   ├── communication_probabilityMap
│   │   │   └── communication_sharedLearn
│   │   ├── pacman_nimble
│   │   │   ├── communication_both
│   │   │   ├── communication_none
│   │   │   ├── communication_probabilityMap
│   │   │   └── communication_sharedLearn
│   │   └── pacman_random2
│   │       ├── communication_both
│   │       │   ├── noise_0
│   │       │   └── noise_3
│   │       ├── communication_none
│   │       │   ├── noise_0
│   │       │   └── noise_3
│   │       ├── communication_probabilityMap
│   │       │   ├── noise_0
│   │       │   └── noise_3
│   │       └── communication_sharedLearn
│   │           ├── noise_0
│   │           └── noise_3
│   ├── ghosts_3
│   │   ├── pacman_bfs
│   │   │   ├── communication_both
│   │   │   ├── communication_none
│   │   │   ├── communication_probabilityMap
│   │   │   └── communication_sharedLearn
│   │   ├── pacman_nimble
│   │   │   ├── communication_both
│   │   │   ├── communication_none
│   │   │   │   └── noise_0
│   │   │   ├── communication_probabilityMap
│   │   │   │   └── noise_0
│   │   │   └── communication_sharedLearn
│   │   │       └── noise_0
│   │   └── pacman_random2
│   │       ├── communication_both
│   │       ├── communication_none
│   │       │   └── noise_0
│   │       ├── communication_probabilityMap
│   │       │   └── noise_0
│   │       └── communication_sharedLearn
│   │           ├── noise_0
│   │           └── noise_3
│   └── ghosts_4
│       ├── pacman_bfs
│       │   ├── communication_both
│       │   ├── communication_none
│       │   ├── communication_probabilityMap
│       │   └── communication_sharedLearn
│       ├── pacman_nimble
│       │   ├── communication_both
│       │   ├── communication_none
│       │   ├── communication_probabilityMap
│       │   └── communication_sharedLearn
│       └── pacman_random2
│           ├── communication_both
│           ├── communication_none
│           ├── communication_probabilityMap
│           └── communication_sharedLearn
└── medium_layout
    ├── ghosts_2
    │   ├── pacman_bfs
    │   │   ├── communication_both
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_none
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_probabilityMap
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   └── communication_sharedLearn
    │   │       ├── noise_0
    │   │       └── noise_3
    │   ├── pacman_nimble
    │   │   ├── communication_both
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_none
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_probabilityMap
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   └── communication_sharedLearn
    │   │       ├── noise_0
    │   │       └── noise_3
    │   └── pacman_random2
    │       ├── communication_both
    │       │   ├── noise_0
    │       │   └── noise_3
    │       ├── communication_none
    │       │   ├── noise_0
    │       │   └── noise_3
    │       ├── communication_probabilityMap
    │       │   ├── noise_0
    │       │   └── noise_3
    │       └── communication_sharedLearn
    │           ├── noise_0
    │           └── noise_3
    ├── ghosts_3
    │   ├── pacman_bfs
    │   │   ├── communication_both
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_none
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_probabilityMap
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   └── communication_sharedLearn
    │   │       ├── noise_0
    │   │       └── noise_3
    │   ├── pacman_nimble
    │   │   ├── communication_both
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_none
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   ├── communication_probabilityMap
    │   │   │   ├── noise_0
    │   │   │   └── noise_3
    │   │   └── communication_sharedLearn
    │   │       ├── noise_0
    │   │       └── noise_3
    │   └── pacman_random2
    │       ├── communication_both
    │       │   ├── noise_0
    │       │   └── noise_3
    │       ├── communication_none
    │       │   ├── noise_0
    │       │   └── noise_3
    │       ├── communication_probabilityMap
    │       │   ├── noise_0
    │       │   └── noise_3
    │       └── communication_sharedLearn
    │           ├── noise_0
    │           └── noise_3
    └── ghosts_4
        ├── pacman_bfs
        │   ├── communication_both
        │   │   ├── noise_0
        │   │   └── noise_3
        │   ├── communication_none
        │   │   ├── noise_0
        │   │   └── noise_3
        │   ├── communication_probabilityMap
        │   │   ├── noise_0
        │   │   └── noise_3
        │   └── communication_sharedLearn
        │       ├── noise_0
        │       └── noise_3
        ├── pacman_nimble
        │   ├── communication_both
        │   │   ├── noise_0
        │   │   └── noise_3
        │   ├── communication_none
        │   │   ├── noise_0
        │   │   └── noise_3
        │   ├── communication_probabilityMap
        │   │   ├── noise_0
        │   │   └── noise_3
        │   └── communication_sharedLearn
        │       ├── noise_0
        │       └── noise_3
        └── pacman_random2
            ├── communication_both
            │   ├── noise_0
            │   └── noise_3
            ├── communication_none
            │   ├── noise_0
            │   └── noise_3
            ├── communication_probabilityMap
            │   ├── noise_0
            │   └── noise_3
            └── communication_sharedLearn
                ├── noise_0
                └── noise_3

```