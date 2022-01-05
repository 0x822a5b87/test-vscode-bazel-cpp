# test-vscode-bazel-cpp

>test integration bazel and vs code

- [bazel-with-visual-studio-code](https://shanee.io/blog/2019/05/28/bazel-with-visual-studio-code/)
- [[vs code]tasks.json和launch.json的关系](https://segmentfault.com/a/1190000020802648)

## note

1. `launch.json` and `tasks.json` under the `.vscode` file.

## Configuring the build task

>Now for the fun part. Let's configure our Build Task in Visual Studio Code.
>What is this?
>The build task configures some operation for Visual Studio Code to run and build our code. In our case the operation will be to call bazel build.

If you don't already have any build tasks set (otherwise skip this step):

1. Go to the Terminal tab and click Configure Tasks...,
2. Select Create tasks.json file from template
3. Finally select Others.
