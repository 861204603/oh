## 更改 build-profile.json5 中字段
```
"products": [
      {
        "name": "default",
        "signingConfig": "default",
        "compatibleSdkVersion": 11,
        "compileSdkVersion": 11,
        "runtimeOS": "OpenHarmony",
        "buildOption": {
          "strictMode": {
            "caseSensitiveCheck": true,
            "useNormalizedOHMUrl": false
          },
          "externalNativeOptions": {
            "abiFilters": ["armeabi-v7a","arm64-v8a","x86_64"]
          }
        }
      }
    ],
```
