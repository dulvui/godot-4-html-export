# godot-html-export
Godot 4.x Github Action for HTML5 export.  
If you are facing problems with the action or this README feels not complete, pull requests are welcome or open an issue.

## Table of contents
- [godot-html-export](#godot-html-export)
  - [Table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Parameters](#parameters)
  - [How to use](#how-to-use)
  - [Working examples](#working-examples)
  - [License](#license)

## Requirements
 - Godot Project

## Parameters
| key | required | default | description |
| ----|----------|---------|-------------|
| godot-version | true | . | Godot Engine version. Supported are 4.x versions. Check versions [here](https://github.com/godotengine/godot-builds/releases) |
| godot-channel | false | stable | Godot Engine release channel (stable, beta, rc1, rc2, rc3...). Defaults to 'stable' Check release channels [here](https://github.com/godotengine/godot-builds/releases) |
| working-directory | false | . | Path to project.godot file |


## How to use
Use the 4.x tag
```
- name: Godot HTML5 export
  uses: dulvui/godot-4-html-export@v1
  with:
    godot-version: 4.2.2
```

 ## Working examples
You an find a working examples here:  
https://github.com/dulvui/condor/blob/main/.github/workflows/upload-itchio.yml  

## License
This software is licensed under the [MIT license](LICENSE).
