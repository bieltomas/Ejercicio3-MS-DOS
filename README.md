# Ejercicio3-MS-DOS

## Task 1 ##

`Get-Help Get-Help`

![image](https://user-images.githubusercontent.com/91564872/160498466-9724cb1e-65a6-4344-aeff-8941af1c940c.png)


`Get-Help New-Item`

![image](https://user-images.githubusercontent.com/91564872/160498644-881b0c2a-a551-45d8-af0d-337c05ff2807.png)

`Get-Help Get-Alias`

![image](https://user-images.githubusercontent.com/91564872/160498995-d3326153-e204-40a2-87e7-708bc936f880.png)

`Get-Help Get-AuthenticodeSignature`

![image](https://user-images.githubusercontent.com/91564872/160499070-8d034d32-1cb6-41f3-b77b-b44f3182c4fa.png)

`Get-Help Get-ControlPanelItem`

![image](https://user-images.githubusercontent.com/91564872/160499198-05e186ca-0e33-4cfa-895e-bf0c98b41d05.png)

## Task 2 ##

`Get-Help Get-Help -Examples`

![image](https://user-images.githubusercontent.com/91564872/160499307-89b91da6-da45-42ae-a469-b14f7c5abcf9.png)

`Get-Help New-Item -Examples`

![image](https://user-images.githubusercontent.com/91564872/160499479-873dbc4f-b8e2-4b4d-929a-609fdae519b5.png)

`Get-Help Get-Alias -Examples`

![image](https://user-images.githubusercontent.com/91564872/160499674-8e4415ed-8f07-4b94-969f-40d536331ef8.png)

`Get-Help Get-AuthenticodeSignature -Examples`

![image](https://user-images.githubusercontent.com/91564872/160500256-2aae49ac-cd9c-4834-88b9-9ceb9234152d.png)

`Get-Help Get-ControlPanelItem -Examples`

![image](https://user-images.githubusercontent.com/91564872/160500864-aa3980f0-d9c6-4241-a72f-7006a23712d3.png)

## Task 3

`New-Item -Path C:\ -Name Expo -ItemType Directory`

![image](https://user-images.githubusercontent.com/91564872/160867248-ffcd2f21-59d1-48d5-bdab-51be2c716e09.png)


`New-Item -Path C:\Sudoblark -Name PowerShell -ItemType Directory`

![image](https://user-images.githubusercontent.com/91564872/160867599-4969215d-93e2-45f4-94b8-173b4a328c65.png)


`New-Item -Path C:\Sudoblark\PowerShell -Name Workshop1 -ItemType Directory`



`New-Item -Path C:\Sudoblark\PowerShell\Workshop1 -Name bclark -ItemType Directory`

![image](https://user-images.githubusercontent.com/91564872/160867748-cf344078-9cf7-4d7e-a055-1aa638e157bd.png)

`New-Item -Path C:\Sudoblark\PowerShell\Workshop1\bclark\ -Name Testfile.txt -ItemType File`

![image](https://user-images.githubusercontent.com/91564872/160869274-488f7523-6b75-4971-9596-46d4ac480994.png)


## Task 4

`Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value True`
`Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Hello"`
`Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value 42`

![image](https://user-images.githubusercontent.com/91564872/160869375-73ad6719-5790-4d24-8b54-d629b5b3eae7.png)

## Task 5

`Get-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt | Get-Member`

![image](https://user-images.githubusercontent.com/91564872/160869682-4a18fe5f-5690-4944-af9d-7150f8147de5.png)


## Task 6

`Set-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Boooooo"`

![image](https://user-images.githubusercontent.com/91564872/160870104-457ce31d-30b9-4cab-be4e-9fea0f931924.png)

## Task 7

`Get-Service | Format-List`

![image](https://user-images.githubusercontent.com/91564872/160870334-6dcf5511-29e3-430f-8cfb-ce0ca33270ab.png)

## Task 8

`Get-Command | Out-GridView`

![image](https://user-images.githubusercontent.com/91564872/160870597-4720b598-21b7-4f3d-a19e-9d46c9fdfa9e.png)

## Task 9

`Get-Help | Out-GridView`

![image](https://user-images.githubusercontent.com/91564872/160871054-01d3a8cf-5a57-4794-a70f-912dd40c6819.png)


`New-Item | Out-GridView`

![image](https://user-images.githubusercontent.com/91564872/160871452-a494de1c-c08f-43b4-b98b-86dad669b4fd.png)


`Get-Alias | Out-GridView`

![image](https://user-images.githubusercontent.com/91564872/160871161-5c9e305f-fa4e-4f1b-8382-c04afe3ee1f7.png)


`Get-AuthenticodeSignature | Out-GridView`

![image](https://user-images.githubusercontent.com/91564872/160871560-1e6ae0f1-4432-4018-b774-50bd6744287e.png)


`Get-ControlPanelItem | Out-GridView`

![image](https://user-images.githubusercontent.com/91564872/160871288-2336afef-6b4d-44b7-9185-052877865f5d.png)

Con `Get-AuthenticodeSignature | Out-GridView` y `New-Item | Out-GridView` nos pide un path en concreto


## Task 10

[Link a la documentaci??n de PowerShell](https://docs.microsoft.com/es-es/powershell/)

![image](https://user-images.githubusercontent.com/91564872/160872025-25b10ba8-91a3-43b2-8e2c-71b7196784ee.png)

