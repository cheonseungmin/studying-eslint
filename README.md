        // vscode에서 파일 저장할 때마다 린트가 자동으로 실행되기 위한 설정
        // F1 => settings 입력 => Open Settings (Json) 
        
        // settings.json
        {
            "workbench.colorTheme": "Visual Studio Dark",
            "eslint.format.enable": true,
            "eslint.lintTask.enable": true,
            "eslint.run": "onSave",
            "editor.codeActionsOnSave": {
                "source.fixAll": true,
            },
            "editor.formatOnSave": true,
            "explorer.confirmDelete": false,
            "workbench.iconTheme": "material-icon-theme",
            "files.autoSave": "afterDelay",
        }
