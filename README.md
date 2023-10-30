# Tetris Game App
# Project Overview 
- Project Name: Tetris Game App
- Group Members: Rahul Dalavi , Sandip Gole , Parth Dalvi
- Date: 18/10/2023
The Tettris Game App is a cloud based solution that utilizes azure services to feel for extra features while playing an game. This Project is designed to be scalable , reliable and easy to use for anyone.

Prerequisites :
- An Azure account with an active subscription. <a href="https://azure.microsoft.com/en-us/free/?WT.mc_id=A261C142F" target="_blank">Create an account for free.</a> 
- An Azure DevOps organization. <a href="https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/pipelines-sign-up?view=azure-devops" target="_blank">Create an account for free.</a> 

Video ---- https://drive.google.com/file/d/1oJmq9Xn8upoyJ1ZqeFr8yHG4eZUeq3aC/view?usp=sharing 

Youtube Video ---- https://youtu.be/DcmHD9m14FQ

Project pdf url ---- https://drive.google.com/file/d/1w1RZnPFtlJU0Cv4Ag4YB6eG4wYYG6bfd/view?usp=sharing 

LOGIN TO THE AZURE PORTAL
![Screenshot2](https://github.com/Rahul12da/GameApp/assets/104122493/1c0402da-8a46-4194-8bf2-2bd33ce31345)

GO TO THE CONTAINER REGISTRIES
![Screenshot3](https://github.com/Rahul12da/GameApp/assets/104122493/7c38f252-f006-4e1c-a903-12aa811fd9f3)

CLICK ON CREATE AND FILL BASICS INFO
![Screenshot4](https://github.com/Rahul12da/GameApp/assets/104122493/6954032c-6636-4531-85e0-e0550a08e6e0)

GIVE THE UNIQUE REGISTRY NAME
![Screenshot5](https://github.com/Rahul12da/GameApp/assets/104122493/9dd248ca-466b-417b-a5d2-6427477ee2d7)

CLICK ON REVIEW AND CREATE
![Screenshot6](https://github.com/Rahul12da/GameApp/assets/104122493/801a5607-b810-4229-9b89-194bb3db481f)

WE HAVE SUCCESSFULLY CREATED CONTAINER REGISTRY
![Screenshot7](https://github.com/Rahul12da/GameApp/assets/104122493/ab16f0aa-ff96-4a61-8352-d6a0f4f299af)

GO INSIDE CONTAINER REGISTRIES
![Screenshot8](https://github.com/Rahul12da/GameApp/assets/104122493/61e3d03c-278b-46ed-80f5-0932d2bb4095)

THEN GO TO THE AZURE DEVOPS PORTAL WHICH IS USED TO CREATE AN CICD PIPELINE WHICH IS LINKED WITH OUR MICROSOFT AZURE PORTAL
![Screenshot9](https://github.com/Rahul12da/GameApp/assets/104122493/3449f87d-290a-4bb3-b176-5ac3f074d814)

THEN CLICK ON CREATE NEW PROJECT
![Screenshot10](https://github.com/Rahul12da/GameApp/assets/104122493/e59a8f65-17f3-4186-b8f3-bb2cf7c71d1a)

THEN SELECT PROJECT AS PRIVATE
![Screenshot11](https://github.com/Rahul12da/GameApp/assets/104122493/2473d49c-05a5-4593-87fd-275ffdec8e13)

THEN WE HAVE SUCCESSFULLY CREATED ONE PROJECT FOLDER INSIDE DEVOPS PORTAL WHICH IS USED FOR CREATION OF CICD PIPELINE
![Screenshot12](https://github.com/Rahul12da/GameApp/assets/104122493/8eb7b1cd-ec26-49e9-8cc3-059fa36ea7af)

THEN GO INSIDE PROJECT FOLDERS SERVICE CONNECTIONS
![Screenshot13](https://github.com/Rahul12da/GameApp/assets/104122493/c8a24304-1c97-4beb-ad1d-852c1bf4786a)

THEN CREATE SERVICE CONNECTIONS INSIDE PROJECT FOLDER
![Screenshot14](https://github.com/Rahul12da/GameApp/assets/104122493/408d8643-2268-41e4-ba17-a474a073a26a)

FIRST CREATE NEW SERVICE CONNECTION DOCKER REGISTRY WHICH IS ONE OF THE SERVICES OF AZURE PORTAL
![Screenshot15](https://github.com/Rahul12da/GameApp/assets/104122493/9075dff8-c558-4316-85c5-ab13fa1e7f6b)

CLICK ON AZURE CONTAINER REGISTRY TO MAKE CONNECTIONS
![Screenshot16](https://github.com/Rahul12da/GameApp/assets/104122493/399bf56e-fd5a-4aae-a7f3-907e6bbcb6d3)

SELECT AUTHENTICATION TYPE AS SERVICE CONNECTION
![Screenshot17](https://github.com/Rahul12da/GameApp/assets/104122493/c65d3856-a8cc-4a92-8fd6-1bc8e44e655d)

THEN SIGN IN TO THE MICROSOFT AZURE ACCOUNT
![Screenshot18](https://github.com/Rahul12da/GameApp/assets/104122493/52a7355b-e57a-4805-8d84-bd97cf594dde)

SIGN IN WITH GITHUB
![Screenshot19](https://github.com/Rahul12da/GameApp/assets/104122493/7fbf4af4-c601-47e7-aa90-da342f4190b4)

THEN OUR AUTHORIZED SUBSCRIPTION DETAILS OF MICROSOFT AZURE ACCOUNT IS SUCCESSFULLY LINKED WITH DEVOPS PORTAL
![Screenshot20](https://github.com/Rahul12da/GameApp/assets/104122493/d6fe89ba-33c6-4b18-8917-38e55e44b5cd)

WHEN OUR SUBSCRIPTION DETAILS ARE LINKED AUTOMATICALLY AZURE CONTAINER REGISTRY SERVICE DESPLAYED ON BELOW TAB
![Screenshot21](https://github.com/Rahul12da/GameApp/assets/104122493/b240cbb6-3b5a-4789-9403-3465f50f8fef)

THEN OUR DOCKER REGISTRY SERVICE CONNECTION SUCCESSFULLY BUILD
![Screenshot22](https://github.com/Rahul12da/GameApp/assets/104122493/4f22b387-6351-4f3a-8a68-0514bc24021e)

THEN CREATE NEW SERVICE CONNECTION WITH GITHUB TO GET CODE FROM GITHUB TO OUR PROJECT
![Screenshot23](https://github.com/Rahul12da/GameApp/assets/104122493/7a4809ab-2167-4eb3-b8fe-0d2db7d4f028)

GIVE GRANT AUTHORIZATION ACCESS
![Screenshot24](https://github.com/Rahul12da/GameApp/assets/104122493/f389c45c-93d0-4c58-b731-b505603eaf1f)

THEN GITHUB ACCOUNT IS BUILD
![Screenshot25](https://github.com/Rahul12da/GameApp/assets/104122493/ccf71b9c-473e-4e7d-8b0f-569cb97f6d3c)

GIVE SERVICE CONNECTION NAME
![Screenshot26](https://github.com/Rahul12da/GameApp/assets/104122493/5a1fe25f-b303-4d41-9829-0328b1e31937)

GIVE GRANT ACCESS PERMISSION TO ALL PIPELINES
![Screenshot27](https://github.com/Rahul12da/GameApp/assets/104122493/f1cbf86e-4c28-4c73-8867-f8ce7b13428c)

GITHUB CONNECTION BUILD SUCCESSFULLY
![Screenshot28](https://github.com/Rahul12da/GameApp/assets/104122493/db1469f7-2271-458e-bc9b-cdbd07c8de55)

GO TO PIPELINES AND CREATE PIPELINE
![Screenshot29](https://github.com/Rahul12da/GameApp/assets/104122493/fc804207-7b94-48f4-b85d-172db242418e)

SELECT GITHUB FOR CODE
![Screenshot30](https://github.com/Rahul12da/GameApp/assets/104122493/17c656ac-9956-4dc6-b5e0-bc9ee7986205)

SELECT GITHUB REPOSITORY
![Screenshot31](https://github.com/Rahul12da/GameApp/assets/104122493/3b338254-9f6a-489f-9fee-763f24ebee66)

THEN WE HAVE TO APPROVE AND GIVE ACCESS TO BUILD AN CONNECTION WITH MICROSOFT AZURE PORTAL
![Screenshot32](https://github.com/Rahul12da/GameApp/assets/104122493/1e48192e-9c00-4257-a422-dce9d771dae8)
![Screenshot33](https://github.com/Rahul12da/GameApp/assets/104122493/c19f23a4-eb5a-4b89-959c-8567d2ac79a9)

THEN LOGIN WITH GITHUB PORTAL
![Screenshot34](https://github.com/Rahul12da/GameApp/assets/104122493/4ae2f137-c9bf-45f5-a1c0-9952cba2ee1e)
![Screenshot35](https://github.com/Rahul12da/GameApp/assets/104122493/afee2b95-2719-4642-8471-134b233b7d39)

THEN SELECT DOCKER CONFIGURATION
![Screenshot38](https://github.com/Rahul12da/GameApp/assets/104122493/a4d92b8a-6256-4eee-ad71-5dde2969c2f4)

THEN OUR CICD PIPELINE IS CREATED SUCCESSFULLY
![Screenshot48](https://github.com/Rahul12da/GameApp/assets/104122493/6a8c860c-1269-4a58-91af-02f389b3722d)

THEN GO TO THE MICROSOFT AZURE PORTAL
![Screenshot49](https://github.com/Rahul12da/GameApp/assets/104122493/f8a244ee-4c3d-4d1d-9d4b-e8d69547cbf2)

THEN GO TO THE CONTAINER REGISTRIES
![Screenshot51](https://github.com/Rahul12da/GameApp/assets/104122493/23fff0e8-40a5-4282-ae45-fa4dc3346ff5)

THEN GIVE ADMINISTRATIVE ACCESS 
![Screenshot53](https://github.com/Rahul12da/GameApp/assets/104122493/99afbfb7-1991-4195-a7c6-f491c5a8b1f3)

GO TO THE APP SERVICES
![Screenshot54](https://github.com/Rahul12da/GameApp/assets/104122493/af658742-9091-43cf-bcd2-1fa7173c2115)

FILL BASICS INFO INSIDE APP SERVICES
![Screenshot56](https://github.com/Rahul12da/GameApp/assets/104122493/1380a679-6d53-4d21-a2fa-ca578eab8a23)

SELECT DOCKER CONTAINER OPTION
![Screenshot57](https://github.com/Rahul12da/GameApp/assets/104122493/c8e8b692-1272-416d-b53a-efd26847e0df)

THEN SELECT DOCKER AS AZURE CONTAINER REGISTRY THEN OUR IMAGE IS REFLECTED IN BELOW SECTION
![Screenshot59](https://github.com/Rahul12da/GameApp/assets/104122493/a0f8f466-c030-425d-8983-29106c2c4e34)

THEN OUR WEB APP IS SUCCESSFULLY CREATED
![Screenshot62](https://github.com/Rahul12da/GameApp/assets/104122493/12f5655e-1599-46ab-90e3-c5d10523bebd)

THEN COPY DEFAULT DOMAIN URL OF WEB APP 
![Screenshot69](https://github.com/Rahul12da/GameApp/assets/104122493/e95fae0a-e1fd-40bb-be7e-1beccd8e2386)

PASTE APP URL IN ANY SEARCH ENGINES WE SAW OUR FINAL OUTPUT
![Screenshot70](https://github.com/Rahul12da/GameApp/assets/104122493/9500677b-5845-4798-9eeb-d1b10e61fe16)
![Screenshot71](https://github.com/Rahul12da/GameApp/assets/104122493/2c546cc3-763c-45d4-949c-fe514e4799e6)
![Screenshot74](https://github.com/Rahul12da/GameApp/assets/104122493/e21d7a83-dd96-4b3d-84e3-4ae7309bee21)


















































