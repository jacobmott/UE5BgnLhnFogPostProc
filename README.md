# UE5BgnLhnFogPostProc
Working through udemy course (Unreal Engine 5- Beginner Lighting, Fog, and Post Processing). In Progress


Finished the course! 

Gifs, youtube video demo fly/walkthrough and screenshots to come soon. 

https://www.udemy.com/course/ue5lighting/

![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/180628089-44794023-1f16-4247-9001-5bc0c1b46f9f.png)


# NightTime Demo/Flythrough video

https://youtu.be/4g1YMw0inGo

![NightTime](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181165836-c8ca7d44-aed6-4cd7-8a75-e65b69362f9a.gif)

![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181165917-5b545156-0702-4343-85e6-dc1575e8b2bd.png)


![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181163958-a75d8721-9842-46e9-9424-71661e1d887e.png)


![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181164013-49a9c3cf-b481-4cf6-b22e-016f5fd09ffc.png)


![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181164027-b54f4253-f942-44f1-bc88-3b1d0d2f6b70.png)


![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181164045-ecef35a0-3a2c-4ba3-98f1-405a5b169410.png)


# DreamSunset Demo/Flythrough video

https://youtu.be/Dk_Eds9Jx4o

![DreamySunset1](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181162781-d8ab6254-b919-4faa-ad61-0baa30fb7029.gif)


![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181162902-905838b8-66a0-4566-9db2-2a4e9ea4b7f4.png)



![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181157836-7022c5d1-6617-47b3-8816-55e6484b5426.png)

![image](https://jacobmottgithub.s3.amazonaws.com/UE5BgnLhnFogPostProc/Screenshots/181157859-cc07099c-d660-4aef-9adb-1b0566a817df.png)



## AWS S3 Screenshots And videos folders (Syncing/Pull/Push to)

<details>
The Content folder is stored in s3 bucket

Pull down from bucket
  
```
  aws s3 cp --recursive s3://<bucket>/UE5BgnLhnFogPostProc/Content UE5BgnLhnFogPostProc/Content 
  aws s3 cp --recursive s3://<bucket>/UE5BgnLhnFogPostProc/Screenshots UE5BgnLhnFogPostProc/Screenshots 
```

Push to bucket
```
  aws s3 cp --recursive UE5BgnLhnFogPostProc/Content s3://<bucket>/UE5BgnLhnFogPostProc/Content
  aws s3 cp --recursive UE5BgnLhnFogPostProc/Screenshots s3://<bucket>/UE5BgnLhnFogPostProc/Screenshots
```

Or just do a sync
```
  aws s3 sync UE5BgnLhnFogPostProc/Content s3://<bucket>/UE5BgnLhnFogPostProc/Content --delete  
  aws s3 sync UE5BgnLhnFogPostProc/Screenshots s3://<bucket>/UE5BgnLhnFogPostProc/Screenshots --delete  

```
</details>
