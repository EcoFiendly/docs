24/06/2023 steam fix for transparent window on launch:

1. copy steam.desktop from\
    `/usr/share/applications`\
    to\
    `/$HOME/.local/share/applictions`
2. edit steam.desktop
3. change these two values to false\
    `PrefersNonDefaultGPU`\
    `X-KDE-RunOnDiscreteGpu`