# Build-Deploy

Installing Jenkins

```
amazon-linux-extras install epel -y
yum install java-1.8.0-openjdk-devel -y
wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
yum -y install jenkins
systemctl start jenkins
systemctl enable jenkins
```

![image](https://user-images.githubusercontent.com/23291976/150800602-7c933d30-e57f-4074-af90-5b1cd7d91d1e.png)
```
[root@ip-172-31-13-24 ~]# cat /var/lib/jenkins/secrets/initialAdminPassword
*******
[root@ip-172-31-13-24 ~]#
```

![image](https://user-images.githubusercontent.com/23291976/150800705-f819714d-9e65-47bd-a0b7-eaddd272718c.png)
![image](https://user-images.githubusercontent.com/23291976/150800777-7aeb15a3-6885-4f30-b1c7-fcd016e482f0.png)
![image](https://user-images.githubusercontent.com/23291976/150800847-64ddef6c-3d38-4160-b115-c79e874b5a59.png)
![image](https://user-images.githubusercontent.com/23291976/150802386-f6841eb0-107a-498b-b6fe-4c05e0f918d5.png)
![image](https://user-images.githubusercontent.com/23291976/150802478-45452fe7-4d06-4e22-92bd-e6e522ad3cf7.png)
![image](https://user-images.githubusercontent.com/23291976/150802564-e3920172-f0fe-462c-b2e7-c000f9a1d25c.png)
![image](https://user-images.githubusercontent.com/23291976/150802589-e9f8b7e0-edcf-4cca-a4d2-f4c8bed44dea.png)
![image](https://user-images.githubusercontent.com/23291976/150802688-39a815cf-bdde-449a-a529-5a094ed77f82.png)
![image](https://user-images.githubusercontent.com/23291976/150802846-93182a31-0fc1-42b0-a741-ba31894b5519.png)
![image](https://user-images.githubusercontent.com/23291976/150802937-5bc6fa84-a8f7-4d59-8477-4a16b7291362.png)
![image](https://user-images.githubusercontent.com/23291976/150802994-6ad9cd6c-87e5-416f-8adf-939812a50ff9.png)
![image](https://user-images.githubusercontent.com/23291976/150803147-a13cafe2-5ef4-4463-a6dc-3ffb0e8e8d99.png)
![image](https://user-images.githubusercontent.com/23291976/150803746-5bb49797-570b-45d2-8551-747f23a85813.png)
![image](https://user-images.githubusercontent.com/23291976/150803997-0e57d8ed-d98f-44e3-aaed-589bfa5ad396.png)
![image](https://user-images.githubusercontent.com/23291976/150804006-bca36540-7e53-418f-9222-7245fa07c9ee.png)

Select Free style project
![image](https://user-images.githubusercontent.com/23291976/150804140-5540d00f-d890-4435-a3bc-1051a98da7d5.png)

![image](https://user-images.githubusercontent.com/23291976/150804523-a4afdf32-4949-448c-b3ee-883cee51ecd2.png)
![image](https://user-images.githubusercontent.com/23291976/150805865-191b782a-4b83-440b-9f8f-2b54709584ee.png)
![image](https://user-images.githubusercontent.com/23291976/150806025-dde53073-985a-4ef7-9188-c80573e154cd.png)
![image](https://user-images.githubusercontent.com/23291976/150806285-6850d715-9c18-41df-8fa0-e74124375d1f.png)
![image](https://user-images.githubusercontent.com/23291976/150806403-5355d0ba-1904-4e33-b067-00aaf616f3fe.png)

Choose advanced >> Disable the host SSH key check
![image](https://user-images.githubusercontent.com/23291976/150806608-e51fd078-148e-4904-af96-d6b3a07151a5.png)


Enable Webhooks for Repository

![image](https://user-images.githubusercontent.com/23291976/150807052-25fa01d6-134d-4036-9096-224d454ca6d2.png)
![image](https://user-images.githubusercontent.com/23291976/150807295-0a4aeb26-bd60-4e1d-a78f-7277f6842b80.png)
![image](https://user-images.githubusercontent.com/23291976/150807341-22e55860-3278-4327-8b9a-7fff50ad0337.png)



