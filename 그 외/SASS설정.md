## 1. CSS전처리기
  - CSS를 생성하도록 하는 프로그램
  - 보다 가독성있고, 유지보수가 수월하게 작성할 수 있다.
  - 종류 : SASS, LESS, Stylus, PostCSS

    
***


## 2. VScode에 SASS설정하기
1. 확장(Extension)에서 __[Live Sass Compiler]__를 설치한다.  
1. 설치 완료 후, 아래 그림과 같이 __[확장 설정]__으로 들어간다.


```json
    "liveSassCompile.settings.formats": [
                {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": null,
            "savePathReplacementPairs": null
        }
    ]
```
