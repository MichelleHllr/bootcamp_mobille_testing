* Settings * 
Library    AppiumLibrary

* Keywords *
Abrir Aplicativo
    Open Application    http://localhost:4723
...    automationName=UiAutomator2
...    platformName=Android    
...    deviceName=Android Emulator
...    app=${EXECDIR}/qazandofood.apk
...    udid=emulator-5554

Efetuar login
    Input Text   accessibility_id=email    teste@teste.com
    Input Text   accessibility_id=password    123456
    Click Element    accessibility_id=login-button

* Test Cases *
Cenário 1 - Realizar login com sucesso
    Abrir Aplicativo
    Sleep    3s
    Efetuar login

Cenário 2 - Realizar login com sucesso 2
    Abrir Aplicativo
    Sleep    3s
    Efetuar login
    
