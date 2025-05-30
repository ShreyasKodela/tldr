# waypipe

> Remotely run graphical applications under a Wayland compositor.
> More information: <https://gitlab.freedesktop.org/mstoeckl/waypipe>.

- Run a graphical program remotely and display it locally:

`waypipe ssh {{user}}@{{server}} {{program}}`

- Open an SSH tunnel to run any program remotely and display it locally:

`waypipe ssh {{user}}@{{server}}`

- Skip testing for Vulkan support:

`waypipe --test-skip-vulkan ssh {{user}}@{{server}} {{program}}`

- Display help:

`waypipe {{[-h|--help]}}`
