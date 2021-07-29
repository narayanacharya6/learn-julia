This repository hosts stuff I did while trying to pick up [Julia](https://docs.julialang.org/en/v1/)!

1. Install Julia:
    a. Download the latest version of Julia from [here](https://julialang.org/downloads/). At the time of this writing it is `1.6`
    b. Follow the instructions for installation based on your OS.
    c. Add julia to your path.
       Since I use macOS, I need to simply change symlink using the terminal as suggested [here](https://julialang.org/downloads/platform/#optional_add_julia_to_path).:

    ```
    rm -f /usr/local/bin/julia
    ln -s /Applications/Julia-1.6.app/Contents/Resources/julia/bin/julia /usr/local/bin/julia
    ```

2. Check setup: 
    In a new terminal window try:
    ```
    julia
    ```

    You should get:
```
                   _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.6.2 (2021-07-14)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

```

3. To follow along, clone this repository.

4. Navigate to the clone directory and try this in the terminal:
    ```
    julia 000-check-installation.jl 
    ```

    You should see:
    ```
    Welcome to learn-julia!
    ```
    

If this works you are all set with Julia and this repository.

