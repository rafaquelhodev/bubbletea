# Download Progress
This example was built based on [this](https://github.com/charmbracelet/bubbles/discussions/127) discussion.

## How to Run
`go build .` in this directory on your machine (in examples/download-progress)
then run `./download-progress --url="https://download.blender.org/demo/color_vortex.blend"` this can be whatever file you'd like to download. 
Note: the current version will not show a TUI for downloads that do not provide the ContentLength header field.

