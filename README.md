# QT_deployment_app
Hướng dẫn deployment app trên windown ios android linux

## Deploy app windown
- Chọn Qt\5.15.2\mingw81_64> cho windon64bit
-Note: tùy vào ứng dụng, nếu viết trên MSVC(microsoft visual studio code) thì chọn ![image](https://user-images.githubusercontent.com/18188862/179348738-880ca59f-1a29-47a2-8a69-0ebd0ac60cc1.png)

![image](https://user-images.githubusercontent.com/18188862/179348636-b83abdcd-fd0f-4409-9090-64263021d274.png)

-Giao diện 
![image](https://user-images.githubusercontent.com/18188862/179348764-c1621ddc-8a1f-4ce6-975f-f907dff1ed15.png)
-Note: gõ lệnh " C:\Qt\5.15.2\mingw81_64>windeployqt.exe " để kiểm tra

- Vào thư mục chứa file source code và file build của QT
![image](https://user-images.githubusercontent.com/18188862/179348852-8072d106-a0fd-4e8f-9eac-5bd5c432448e.png)
- Đường dẫn tới thư mục build realease
![image](https://user-images.githubusercontent.com/18188862/179348906-5fde4a78-c071-455a-8c06-d59fe14e996d.png)

D:\Develop_firmware\PROJECT_FREELANCER\Project_Nhat\Edge_Clock\code\dev_GUI_Edge_Clock\build-qml_rgb-Desktop_Qt_5_15_2_MinGW_64_bit-Release\
release>windeployqt.exe --quick .  

- Đường dẫn thư mục qml: " --qmldir D:\Develop_firmware\PROJECT_FREELANCER\Project_Nhat\Edge_Clock\code\dev_GUI_Edge_Clock\Dev_GUI_EdgeClock\qml "

- cmd_deloy_windown

D:\Develop_firmware\PROJECT_FREELANCER\Project_Nhat\Edge_Clock\code\dev_GUI_Edge_Clock\build-qml_rgb-Desktop_Qt_5_15_2_MinGW_64_bit-Release\release>windeployqt.exe --quick --no-translations . --qmldir D:\Develop_firmware\PROJECT_FREELANCER\Project_Nhat\Edge_Clock\code\dev_GUI_Edge_Clock\Dev_GUI_EdgeClock\qml

https://www.youtube.com/watch?v=8qozxqSZQEg

## Deploy app macos

## Deploy app ubuntu
