# blasteroids

See [Documentation](documentation/)

## Game development project for CMU 24780
## Contributions:
* menu-Author: Jeremy Kilbride

* ship-Author: Vignesh Menon
   
* sound-Author: Reid Graves
 
* asteroid-Author: Anton Yanonvich
   
* game-Author: Nikole Chetty

* summary-Author: Khai Nguyen

## Playing the game:
See [/documentation/user_guid.pdf](/documentation/user_guid.pdf) and [/documentation/nullptr_blasteroids_user_guide.pdf](/documentation/nullptr_blasteroids_user_guide.pdf)

Compile and execute integrate.cpp file. Make sure to include all the scripts in the `integrate` and `library` folders. 

<!-- {
    "tasks": [
        {
            "type": "cppbuild",
            "label": "C/C++: g++.exe build active file",
            "command": "C:\\Strawberry\\c\\bin\\g++.exe",
            "args": [
                "-fdiagnostics-color=always",
                "-I../libraries",
                "-g",
                "${file}",
                "-o",
                "${fileDirname}\\${fileBasenameNoExtension}.exe",
                // Edit Below lines to include other .cpp or .c files that need to be compiled
                "../libraries/fssimplewindow.cpp",
                "../libraries/yssimplesound.cpp",
                "../libraries/ysglfontdata.c",
                // "yspng.cpp",
                // Requried to run the integrate.cpp
                "asteroid_manager.cpp",
                "asteroid.cpp",
                "../libraries/mmlplayer.cpp",
                "menu.cpp",
                "background.cpp",
                "ship.cpp",
                "summary.cpp",
                "explosion.cpp",
                "SoundManager.cpp",
                //"PlayerStats.cpp",
                // Add Required libraries if necessary
                // Require when using 'yssimplewindow'
                "-lgdi32",
                "-lopengl32",
                "-lglu32",
                "-luser32",
                "-lkernel32",
                "-limm32",
                // Required if using 'yssimplesound'
                "-ldsound",
                "-luuid"
            ],
            "options": {
                "cwd": "${fileDirname}"
            },
            "problemMatcher": [
                "$gcc"
            ],
            "group": {
                "kind": "build",
                "isDefault": true
            },
            "detail": "Task generated by Debugger."
        }
    ],
    "version": "2.0.0"
} -->