# EJC3-Primitive-Datatype-tasks

## Task 1

#### Use “Get-Help” to find out more information about 5 cmdlets

```
Get-Help Invoke-Command
```
<img width="935" alt="2022-03-30" src="https://user-images.githubusercontent.com/91699247/160718410-53146414-4512-451d-8e3e-c54ae3bcecab.png">
<img width="933" alt="2022-03-30 (1)" src="https://user-images.githubusercontent.com/91699247/160718429-5e951870-eb94-433c-a386-d396198e7f59.png">




```
Get-Help Get-Service
```
<img width="943" alt="2022-03-30 (2)" src="https://user-images.githubusercontent.com/91699247/160718586-eebf92cf-ecbf-4438-b090-e8f171434d21.png">




```
Get-Help Stop-Process
```
<img width="918" alt="2022-03-30 (3)" src="https://user-images.githubusercontent.com/91699247/160718688-b63fa3d0-e5e8-47b5-8e33-31816b7bc32f.png">



```
Get-Help Get-History
```
<img width="935" alt="2022-03-30 (4)" src="https://user-images.githubusercontent.com/91699247/160718755-401844e6-2b2f-4e5a-95a2-8451ece433b8.png">




```
Get-Help Remove-Item
```
<img width="933" alt="2022-03-30 (5)" src="https://user-images.githubusercontent.com/91699247/160718838-b673b14b-0d7e-4f47-9f80-92236271e8ec.png">



## Task 2

#### Use “Get-Help” with the “–Example” parameter for the 5 cmdlets you discovered more about in task 1

```
Get-Help -Examples Invoke-Command
```
<img width="941" alt="2022-03-30 (14)" src="https://user-images.githubusercontent.com/91699247/160719735-467d1939-6e20-4b6c-90ab-88ad03128e40.png">

<img width="942" alt="2022-03-30 (8)" src="https://user-images.githubusercontent.com/91699247/160719029-9172bec5-9a6a-4a99-9fe1-ac0922799166.png">



```
Get-Help -Examples Get-Service
```
<img width="933" alt="2022-03-30 (15)" src="https://user-images.githubusercontent.com/91699247/160719758-93fd36e9-a9ef-473f-a650-4c389b75f1c9.png">

<img width="933" alt="2022-03-30 (10)" src="https://user-images.githubusercontent.com/91699247/160719282-988de368-bafb-4d8b-868f-5a59d6daccec.png">





```
Get-Help -Examples Stop-Process
```
<img width="939" alt="2022-03-30 (16)" src="https://user-images.githubusercontent.com/91699247/160719773-e4652bf9-1c8a-41cf-aded-49360553f225.png">





```
Get-Help -Examples Get-History
```
<img width="498" alt="2022-03-30 (12)" src="https://user-images.githubusercontent.com/91699247/160719421-e248199f-c779-4be9-90d2-55a9878054cc.png">



```
Get-Help -Examples Remove-Item
```
<img width="934" alt="2022-03-30 (13)" src="https://user-images.githubusercontent.com/91699247/160719501-92eb6579-0e80-4d27-8f8f-340009ee2a13.png">




## Task 3

#### Create a new text file named “TestFile.txt” under C:\Maximo\PowerShell\Workshop1\%USERNAME%
```
New-Item -Path C:\Maximo\PowerShell\Workshop1\juans -Name dir3 -ItemType Directory
New-Item -Path C:\Maximo\PowerShell\Workshop1\juans\dir3\ -Name Testfile.txt -ItemType File
```
<img width="498" alt="2022-03-26 (16)" src="https://user-images.githubusercontent.com/91699247/160217489-52b289f1-3b9c-4993-8fed-b2ca1ab739d3.png">



## Task 4
#### Populate the text file you created in task 3 with all three datatypes we’ve covered: “Boolean”, “String” and “Int”
```
Add-Content -Path C:\Maximo\PowerShell\Workshop1\juans\dir3\Testfile.txt -Value False
Add-Content -Path C:\Maximo\PowerShell\Workshop1\juans\dir3\Testfile.txt -Value "Primer string"
Add-Content -Path C:\Maximo\PowerShell\Workshop1\juans\dir3\Testfile.txt -Value 34
```

## Task 5
#### Read from the text file and use “Get-Member” to find the datatype returned
```
Get-Content -Path C:\Maximo\PowerShell\Workshop1\juans\dir3\Testfile.txt | Get-Member
```

## Task 6
#### Overwrite all data within the text file that you created in task 3.
