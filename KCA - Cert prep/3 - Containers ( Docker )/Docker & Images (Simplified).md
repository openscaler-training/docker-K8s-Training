---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Image ^I2bPJ7jt

Container Runtime ^BlZPP3me

the runtime for running containers is the software and OS features that make process isolation and execution possible ^KLefts78

Container Image ^eiKvmwk0

Image are the template for creating containers contain everything require by the processes to run correctly
" libraries, packages, App binary, configuration files..."  ^QvRwcGh2

Image are immutable, that mean they don't changes between execution. 
developers create their own images template and the can be sure if can passed all test it work in production as expected     ^l6KaB3d0

Fast workflow and less time to market. ^Zw9jV2WX

Container image are build up from a series of layers, all those layers packages together contain everything require to run the Application   ^2l0YtSpm

All those layers are read-only and the change are stored in next upper layer during the image build.
worthy noting each upper layers contain delta changes.  ^qNFmEfov

Meta-information contain architecture to run (will it run in Linux, Windows, require ARN or AMD cpu...) ^Txy77srp

Base Image ^QcFmNrin

Update Package cache ^VVspr5QR

Install Software packages for app runtime ^gavpTqs9

Copy custom config file for App run time ^5Nq4CgHM

Add App code ^KmhPbQxG

Define initial processes to run ^zJtU0Gwy

Layer 5 ^e9AzfN8n

Layer 4 ^qJ7l3PA4

Layer 3 ^frI3tePZ

Layer 2 ^VDx0zwCK

Layer 1 ^FrLi6d5B

Base Layer ^q25nJtGC

Image can be build with reproducible methods using Dockerfile or store changes made on running container to obtain new image  ^MxfXIhjW

Image ^3ZwT0cWB

Base Image ^2m6jw39f

Update Package cache ^7lbftrHc

Install Software packages for app runtime ^3Bvns27c

Copy custom config file for App run time ^hGkFwCh9

Add App code ^esEvXHdI

Define initial processes to run ^cXTO4K20

Layer 5 ^wMHM4kJV

Layer 4 ^kb4Ol6xl

Layer 3 ^yJR8P3JA

Layer 2 ^3Bj9dEP6

Layer 1 ^vO2cusBw

Base Layer ^t0BtGgEL

Container (Process Execution) ^9YOUBmKK

Read only Layers ^G6g5DSvp

Read-write Layers ^WRMWD45a

All the contain will be removed after stopping
     except those stored in Disk explicitly   ^lmyHtsPx

What is a container? ^JaNh05eS

Simply put, a container is a sandboxed process on your machine that is isolated from all other processes on the host machine.
 That isolation leverages kernel namespaces and cgroups, features that have been in Linux for a long time.
 Docker has worked to make these capabilities approachable and easy to use. To summarize, a container: ^ikU3dEK7

* is a runnable instance of an image. You can create, start, stop, move, or delete a container using the DockerAPI or CLI. ^eq78FnbK

* can be run on local machines, virtual machines or deployed to the cloud. ^ZQHl0dpT

* is portable (can be run on any OS). ^4kz5X8FA

* is isolated from other containers and runs its own software, binaries, and configurations. ^SRB7Pgo0

What is a container image? ^wDgpFbo2

When running a container, it uses an isolated filesystem. This custom filesystem is provided by a container image. 
Since the image contains the container’s filesystem, it must contain everything needed to run an application - all dependencies,
 configurations, scripts, binaries, etc. The image also contains other configuration for the container, 
such as environment variables, a default command to run, and other metadata. ^YbCs3Zdp

Note ^MiXlaLXJ

If you’re familiar with chroot, think of a container as an extended version of chroot. The filesystem is simply coming from the image. But, 
a container adds additional isolation not available when simply using chroot. ^fQG7biKQ

Copied from Docker Web site ^mjFkEbkj

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://excalidraw.com",
	"elements": [
		{
			"type": "text",
			"version": 111,
			"versionNonce": 381254088,
			"isDeleted": false,
			"id": "I2bPJ7jt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260,
			"y": -160,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 83,
			"height": 35,
			"seed": 2072075074,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011617,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Image",
			"rawText": "Image",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Image"
		},
		{
			"type": "text",
			"version": 463,
			"versionNonce": 951224264,
			"isDeleted": false,
			"id": "BlZPP3me",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -960,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 247,
			"height": 35,
			"seed": 1473813192,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011619,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Container Runtime",
			"rawText": "Container Runtime",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Container Runtime"
		},
		{
			"type": "text",
			"version": 633,
			"versionNonce": 1198569656,
			"isDeleted": false,
			"id": "KLefts78",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -915,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 1191,
			"height": 25,
			"seed": 269929656,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011619,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "the runtime for running containers is the software and OS features that make process isolation and execution possible",
			"rawText": "the runtime for running containers is the software and OS features that make process isolation and execution possible",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "the runtime for running containers is the software and OS features that make process isolation and execution possible"
		},
		{
			"type": "text",
			"version": 489,
			"versionNonce": 798904008,
			"isDeleted": false,
			"id": "eiKvmwk0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -880,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 225,
			"height": 35,
			"seed": 2060552904,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Container Image",
			"rawText": "Container Image",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Container Image"
		},
		{
			"type": "text",
			"version": 849,
			"versionNonce": 1531503032,
			"isDeleted": false,
			"id": "QvRwcGh2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -835,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 1078,
			"height": 50,
			"seed": 2096588216,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Image are the template for creating containers contain everything require by the processes to run correctly\n\" libraries, packages, App binary, configuration files...\" ",
			"rawText": "Image are the template for creating containers contain everything require by the processes to run correctly\n\" libraries, packages, App binary, configuration files...\" ",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Image are the template for creating containers contain everything require by the processes to run correctly\n\" libraries, packages, App binary, configuration files...\" "
		},
		{
			"type": "text",
			"version": 1097,
			"versionNonce": 58275272,
			"isDeleted": false,
			"id": "l6KaB3d0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -760,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 1267,
			"height": 50,
			"seed": 1570865336,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Image are immutable, that mean they don't changes between execution. \ndevelopers create their own images template and the can be sure if can passed all test it work in production as expected    ",
			"rawText": "Image are immutable, that mean they don't changes between execution. \ndevelopers create their own images template and the can be sure if can passed all test it work in production as expected    ",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Image are immutable, that mean they don't changes between execution. \ndevelopers create their own images template and the can be sure if can passed all test it work in production as expected    "
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 1949559480,
			"isDeleted": false,
			"id": "Zw9jV2WX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -478.2398022532526,
			"y": -689.0579235542283,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 395,
			"height": 25,
			"seed": 218415048,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Fast workflow and less time to market.",
			"rawText": "Fast workflow and less time to market.",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Fast workflow and less time to market."
		},
		{
			"type": "text",
			"version": 208,
			"versionNonce": 157236424,
			"isDeleted": false,
			"id": "2l0YtSpm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -640,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 1392,
			"height": 25,
			"seed": 746143944,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Container image are build up from a series of layers, all those layers packages together contain everything require to run the Application  ",
			"rawText": "Container image are build up from a series of layers, all those layers packages together contain everything require to run the Application  ",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Container image are build up from a series of layers, all those layers packages together contain everything require to run the Application  "
		},
		{
			"type": "text",
			"version": 403,
			"versionNonce": 752210872,
			"isDeleted": false,
			"id": "qNFmEfov",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -600,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 996,
			"height": 50,
			"seed": 1625834424,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "All those layers are read-only and the change are stored in next upper layer during the image build.\nworthy noting each upper layers contain delta changes. ",
			"rawText": "All those layers are read-only and the change are stored in next upper layer during the image build.\nworthy noting each upper layers contain delta changes. ",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "All those layers are read-only and the change are stored in next upper layer during the image build.\nworthy noting each upper layers contain delta changes. "
		},
		{
			"type": "text",
			"version": 532,
			"versionNonce": 317481928,
			"isDeleted": false,
			"id": "Txy77srp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -520,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 1008,
			"height": 25,
			"seed": 561907640,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Meta-information contain architecture to run (will it run in Linux, Windows, require ARN or AMD cpu...)",
			"rawText": "Meta-information contain architecture to run (will it run in Linux, Windows, require ARN or AMD cpu...)",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Meta-information contain architecture to run (will it run in Linux, Windows, require ARN or AMD cpu...)"
		},
		{
			"type": "rectangle",
			"version": 159,
			"versionNonce": 726834360,
			"isDeleted": false,
			"id": "r4l6RaV5On1fwhjoXWyu-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": 20,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 80,
			"seed": 1839590584,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 1581034184,
			"isDeleted": false,
			"id": "QcFmNrin",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260,
			"y": 45,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 167,
			"height": 35,
			"seed": 428235464,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Base Image",
			"rawText": "Base Image",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Base Image"
		},
		{
			"type": "rectangle",
			"version": 190,
			"versionNonce": 827213240,
			"isDeleted": false,
			"id": "LgyQ5iiaf-vgDXXzP4QBy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -40,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1823970744,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 99357128,
			"isDeleted": false,
			"id": "VVspr5QR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260,
			"y": -26,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 318,
			"height": 35,
			"seed": 209699272,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Update Package cache",
			"rawText": "Update Package cache",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Update Package cache"
		},
		{
			"type": "rectangle",
			"version": 203,
			"versionNonce": 736939704,
			"isDeleted": false,
			"id": "jxps-uiF9f8qTTn4rfbar",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -100,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1774647752,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 203,
			"versionNonce": 1897306312,
			"isDeleted": false,
			"id": "1ixR9x4E_tXbiOTctFyE4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -160,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1513631416,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 203,
			"versionNonce": 1137850296,
			"isDeleted": false,
			"id": "tfRVxH1YQ4ZdK3h2Hm104",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -220,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 228515784,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 203,
			"versionNonce": 1129856968,
			"isDeleted": false,
			"id": "QIT5z5fPw7er6av4gmB2Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -280,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1560873400,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 300,
			"versionNonce": 1830977720,
			"isDeleted": false,
			"id": "gavpTqs9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -440,
			"y": -89,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 597,
			"height": 35,
			"seed": 143299784,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Install Software packages for app runtime",
			"rawText": "Install Software packages for app runtime",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Install Software packages for app runtime"
		},
		{
			"type": "text",
			"version": 392,
			"versionNonce": 1288505032,
			"isDeleted": false,
			"id": "5Nq4CgHM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -447,
			"y": -150,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 557,
			"height": 35,
			"seed": 1636455864,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Copy custom config file for App run time",
			"rawText": "Copy custom config file for App run time",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Copy custom config file for App run time"
		},
		{
			"type": "text",
			"version": 467,
			"versionNonce": 2004986296,
			"isDeleted": false,
			"id": "KmhPbQxG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -242,
			"y": -209,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 187,
			"height": 35,
			"seed": 281212856,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Add App code",
			"rawText": "Add App code",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Add App code"
		},
		{
			"type": "text",
			"version": 570,
			"versionNonce": 2047929800,
			"isDeleted": false,
			"id": "zJtU0Gwy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -360,
			"y": -266,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 421,
			"height": 35,
			"seed": 1383868600,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Define initial processes to run",
			"rawText": "Define initial processes to run",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Define initial processes to run"
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 504607416,
			"isDeleted": false,
			"id": "JpeZoWLcNjVP-TYgu5nY9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 30,
			"angle": 0,
			"x": 257.30855266632693,
			"y": -96.0291040235962,
			"strokeColor": "#00000000",
			"backgroundColor": "black",
			"width": 40,
			"height": 380,
			"seed": 1338630053,
			"groupIds": [
				"OHcSwjQxLPsQ8c129DYAp"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274011620,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0
				],
				[
					-1.1430204249753615,
					-0.10628442999907328
				],
				[
					-2.225198719169029,
					-0.42607512276248016
				],
				[
					-3.24829798204906,
					-0.9608889664027789
				],
				[
					-4.214020516550143,
					-1.712191717972555
				],
				[
					-5.124099023873654,
					-2.681449134524394
				],
				[
					-5.980296603487666,
					-3.8701610604841967
				],
				[
					-6.78431555832686,
					-5.279810296591207
				],
				[
					-7.537903788725963,
					-6.91184555621135
				],
				[
					-8.528856884580435,
					-9.626870753451938
				],
				[
					-9.3794155857233,
					-12.629576337792324
				],
				[
					-10.100082493296227,
					-15.85729267339117
				],
				[
					-10.701390606707605,
					-19.24729899334716
				],
				[
					-11.19388812449914,
					-22.736891574445647
				],
				[
					-11.588077647812518,
					-26.263366693471973
				],
				[
					-12.123664708638316,
					-33.176115565076195
				],
				[
					-12.286097846700777,
					-36.43699891491144
				],
				[
					-12.392354987918587,
					-39.48393286612925
				],
				[
					-12.45292353430007,
					-42.254213695514956
				],
				[
					-12.478366883520295,
					-44.68515472354058
				],
				[
					-12.479172437587607,
					-46.71403518330479
				],
				[
					-12.465903594177057,
					-48.27813430790628
				],
				[
					-12.449047755296988,
					-49.31478246150372
				],
				[
					-12.439168318622471,
					-49.761241833509125
				],
				[
					-12.439168318622471,
					-126.66498076199474
				],
				[
					-12.439168318622471,
					-126.66498076199474
				],
				[
					-12.551763498445318,
					-133.72092216705585
				],
				[
					-12.888834678646617,
					-140.3557907713886
				],
				[
					-13.449333119025553,
					-146.56454164374225
				],
				[
					-14.232255676781307,
					-152.34213837470932
				],
				[
					-15.236538412579712,
					-157.68353603303908
				],
				[
					-16.461147785353276,
					-162.5836982093241
				],
				[
					-17.905050254034506,
					-167.03758849415695
				],
				[
					-19.567197078422588,
					-171.0401619562869
				],
				[
					-20.797475727933993,
					-173.45235066806708
				],
				[
					-22.05860861813659,
					-175.54521738846697
				],
				[
					-23.335958983618745,
					-177.34134074138666
				],
				[
					-24.61492045723552,
					-178.86329935072632
				],
				[
					-25.880841074441932,
					-180.13366757946446
				],
				[
					-27.119099268959673,
					-181.17502831242282
				],
				[
					-28.315043076243796,
					-182.0099559125799
				],
				[
					-29.454081328282655,
					-182.66102900383586
				],
				[
					-30.52154686139795,
					-183.1508262100908
				],
				[
					-31.50281810931139,
					-183.5019261552449
				],
				[
					-32.38325830661137,
					-183.73690746319826
				],
				[
					-33.14826108615287,
					-183.87834023600772
				],
				[
					-33.78315928425761,
					-183.94881161941674
				],
				[
					-34.273346533780625,
					-183.9708959764038
				],
				[
					-34.60420126844366,
					-183.96716766994737
				],
				[
					-34.76105632456836,
					-183.96021384579092
				],
				[
					-35.301415913264634,
					-183.77369199992782
				],
				[
					-35.79882275112672,
					-183.3633652436373
				],
				[
					-36.24304782141323,
					-182.7545477125281
				],
				[
					-36.623877306515965,
					-181.972553542209
				],
				[
					-36.93105179142685,
					-181.04270539013203
				],
				[
					-37.15438785680439,
					-179.99030887006265
				],
				[
					-37.28362608764047,
					-178.84068237853123
				],
				[
					-37.30855266632696,
					-177.61914431206816
				],
				[
					-37.22550460172761,
					-176.4111602374199
				],
				[
					-37.04282621804904,
					-175.29819471588974
				],
				[
					-36.77167367916681,
					-174.30332063829098
				],
				[
					-36.42321834808979,
					-173.4496151563585
				],
				[
					-36.00863158782687,
					-172.7601596827488
				],
				[
					-35.539054363120215,
					-172.2580313691968
				],
				[
					-35.02568843524543,
					-171.96630310651574
				],
				[
					-34.47965956981133,
					-171.90805204644047
				],
				[
					-34.394802808343854,
					-171.92143560138865
				],
				[
					-34.174400175701976,
					-171.93041336333573
				],
				[
					-33.829866221028055,
					-171.91837199871188
				],
				[
					-33.37264589173125,
					-171.86871095671222
				],
				[
					-32.814184135220614,
					-171.7648211646886
				],
				[
					-32.1659106997719,
					-171.59009354999282
				],
				[
					-30.64570858169668,
					-170.96169282291362
				],
				[
					-28.903538320244976,
					-169.8506574988975
				],
				[
					-27.030883499022877,
					-168.12412351860226
				],
				[
					-25.119273299036486,
					-165.6492353445291
				],
				[
					-24.177443802154393,
					-164.0896357532053
				],
				[
					-23.26019130389185,
					-162.2931289173358
				],
				[
					-21.985667977211932,
					-159.2043953245893
				],
				[
					-20.88040219946658,
					-155.7178279978726
				],
				[
					-19.94462195765597,
					-151.83739811617698
				],
				[
					-19.17852484051359,
					-147.5670683366504
				],
				[
					-18.582323635906278,
					-142.91080983828422
				],
				[
					-18.156200733434176,
					-137.87258527822635
				],
				[
					-17.90038412009747,
					-132.45635731362478
				],
				[
					-17.815071384629647,
					-126.66609712347083
				],
				[
					-17.810086068892346,
					-50.1655862557827
				],
				[
					-17.810086068892346,
					-50.1655862557827
				],
				[
					-17.826151552838454,
					-49.5517067497361
				],
				[
					-17.848874257189856,
					-48.27312346402884
				],
				[
					-17.86509173246941,
					-46.39792592685951
				],
				[
					-17.861565533533273,
					-43.99420366642666
				],
				[
					-17.825102812637624,
					-41.12997803618224
				],
				[
					-17.742480323771936,
					-37.87335560801149
				],
				[
					-17.600490020059055,
					-34.29240886642631
				],
				[
					-17.385939053755152,
					-30.455176208565295
				],
				[
					-17.08560417884972,
					-26.429730118940377
				],
				[
					-16.68629254759894,
					-22.28417716943677
				],
				[
					-16.17478091399228,
					-18.08653871350642
				],
				[
					-15.537861231152597,
					-13.904921323034564
				],
				[
					-14.762325452202717,
					-9.807363395159792
				],
				[
					-13.834980729398808,
					-5.861954458080676
				],
				[
					-12.742588617597022,
					-2.1367669963091336
				],
				[
					-11.47197146818688,
					1.3001605930162405
				],
				[
					-10.302063776323472,
					3.835971425048319
				],
				[
					-9.045490626124497,
					6.018262108420878
				],
				[
					-10.302063776323472,
					8.220783647856443
				],
				[
					-11.47197146818688,
					10.754225407443062
				],
				[
					-12.742497422796951,
					14.194306078800164
				],
				[
					-13.83481353893201,
					17.921487651910684
				],
				[
					-14.762127863469225,
					21.86715224428967
				],
				[
					-15.537648443285761,
					25.962647886078827
				],
				[
					-16.174598524392138,
					30.13933965110654
				],
				[
					-16.686186153665517,
					34.3285755695145
				],
				[
					-17.085619377983065,
					38.46173775881777
				],
				[
					-17.3861214433553,
					42.47017424915804
				],
				[
					-17.60093079492607,
					46.28525011436369
				],
				[
					-17.74322508130586,
					49.83834747194976
				],
				[
					-17.82622754850518,
					53.06079730837129
				],
				[
					-17.86317664166789,
					55.88398174114333
				],
				[
					-17.86726520853781,
					58.23921471303427
				],
				[
					-17.851716495125444,
					60.05794651630575
				],
				[
					-17.829753747441316,
					61.27145700635289
				],
				[
					-17.81456981322924,
					61.81116238806402
				],
				[
					-17.81456981322924,
					138.71599211249574
				],
				[
					-17.81456981322924,
					138.71599211249574
				],
				[
					-17.899669760830236,
					144.48415516289765
				],
				[
					-18.15460482443291,
					149.88056131991598
				],
				[
					-18.57882783523683,
					154.90187002096584
				],
				[
					-19.17180682357491,
					159.54467252871558
				],
				[
					-19.932994620646724,
					163.80562828058027
				],
				[
					-20.86184405765183,
					167.68136262660164
				],
				[
					-21.957807965789783,
					171.1685009168214
				],
				[
					-23.220354375393505,
					174.26373667602786
				],
				[
					-24.129961709583313,
					176.05291472663444
				],
				[
					-25.067277063861816,
					177.60791252256058
				],
				[
					-26.977853722780722,
					180.081019631378
				],
				[
					-28.857712933208546,
					181.81408986550656
				],
				[
					-30.612468077070247,
					182.9381550879727
				],
				[
					-32.14771733715742,
					183.5843153365495
				],
				[
					-32.80352954274548,
					183.7691370746685
				],
				[
					-33.36908929452841,
					183.88360247426337
				],
				[
					-33.832571666763556,
					183.94414164927244
				],
				[
					-34.18218213197483,
					183.96708245151407
				],
				[
					-34.406126162686206,
					183.96885499492652
				],
				[
					-34.492609231421625,
					183.96578713132809
				],
				[
					-35.02132628397527,
					184.02434923868483
				],
				[
					-35.5253295457093,
					184.31678481436222
				],
				[
					-35.99171495241342,
					184.81970992026547
				],
				[
					-36.40759363901071,
					185.50970653092654
				],
				[
					-36.76007674042427,
					186.36339070825073
				],
				[
					-37.036244993310476,
					187.35734442676994
				],
				[
					-37.223194333459105,
					188.4681496610162
				],
				[
					-37.3080662940599,
					189.6724224728947
				],
				[
					-37.27990229997084,
					190.89288678709832
				],
				[
					-37.14870338093323,
					192.04190396683168
				],
				[
					-36.92451616408832,
					193.09407891897456
				],
				[
					-36.61740247571083,
					194.02415289989972
				],
				[
					-36.237393743808724,
					194.8067649038602
				],
				[
					-35.794551794656655,
					195.41662209985552
				],
				[
					-35.29892325539598,
					195.82843165688527
				],
				[
					-34.76055475316798,
					196.01683256920242
				],
				[
					-34.60859381798048,
					196.02296829639928
				],
				[
					-34.293394190663236,
					196.02910402359618
				],
				[
					-33.87775869019947,
					196.01662804496252
				],
				[
					-33.34866165931217,
					195.96904207181348
				],
				[
					-32.715952136409186,
					195.8711090482768
				],
				[
					-31.98952475729834,
					195.7076260058536
				],
				[
					-30.29501897801788,
					195.12312981560535
				],
				[
					-28.344119018333572,
					194.0938274909575
				],
				[
					-26.21584517250826,
					192.49792484705225
				],
				[
					-23.989187336538066,
					190.2137299611517
				],
				[
					-22.86364591490993,
					188.7754814188326
				],
				[
					-21.743150605552465,
					187.11948273577138
				],
				[
					-20.63755044687351,
					185.23053094346906
				],
				[
					-19.55674007468094,
					183.09342307342678
				],
				[
					-17.89190300369073,
					179.08894071839114
				],
				[
					-16.44743816707571,
					174.63348241438578
				],
				[
					-15.223847136236287,
					169.73222944215462
				],
				[
					-14.221616283439516,
					164.3902267329485
				],
				[
					-13.441231980952438,
					158.6126214801381
				],
				[
					-12.883195800175471,
					152.40449270234748
				],
				[
					-12.548024511642346,
					145.77095350557406
				],
				[
					-12.436189288486773,
					138.7171169958152
				],
				[
					-12.441660976491121,
					61.424679749408
				],
				[
					-12.441660976491121,
					61.424679749408
				],
				[
					-12.47839728178699,
					59.762477164403265
				],
				[
					-12.494432367466402,
					57.784148279266574
				],
				[
					-12.48443133772512,
					55.5291662722978
				],
				[
					-12.443013699358858,
					53.03700432179677
				],
				[
					-12.244467420467686,
					47.499203740263944
				],
				[
					-11.855901576492101,
					41.486685354246795
				],
				[
					-11.234409013998018,
					35.315422070697366
				],
				[
					-10.337097778684658,
					29.301352709194347
				],
				[
					-9.771598823435085,
					26.452006217402335
				],
				[
					-9.121060717117906,
					23.760450176689766
				],
				[
					-8.380102966528845,
					21.26617480904315
				],
				[
					-7.543390675863662,
					19.00867033644899
				],
				[
					-6.788905696597176,
					17.373311557930542
				],
				[
					-5.983762005890419,
					15.961190987258124
				],
				[
					-5.126348495608781,
					14.770689474199237
				],
				[
					-4.215008460217597,
					13.800221955894685
				],
				[
					-3.2481459907156065,
					13.048203369485268
				],
				[
					-2.2241043815681607,
					12.513014564738498
				],
				[
					-1.141257325507297,
					12.193070478795164
				],
				[
					0.0020062856015954367,
					12.086786048796093
				],
				[
					0.5466824281679479,
					11.964361247531933
				],
				[
					1.052767971170283,
					11.613210171317867
				],
				[
					1.509775512600271,
					11.05751781152156
				],
				[
					1.9072024513162305,
					10.321400984764033
				],
				[
					2.234576584443161,
					9.42906172609959
				],
				[
					2.4813953108393747,
					8.404633895835914
				],
				[
					2.6371864276298993,
					7.27230248534066
				],
				[
					2.6914473336730396,
					6.056235442294824
				],
				[
					2.6360312934956482,
					4.83488485638502
				],
				[
					2.4788418564373487,
					3.697678951505587
				],
				[
					2.230624809773346,
					2.6689049811441308
				],
				[
					1.9021107416455152,
					1.7727649803549639
				],
				[
					1.5040454393290545,
					1.033563246312342
				],
				[
					1.047174690099176,
					0.47553590144389624
				],
				[
					0.5422442812310919,
					0.12291906817724829
				],
				[
					0,
					0
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 1227167416,
			"isDeleted": false,
			"id": "e9AzfN8n",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -613,
			"y": -260,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 109,
			"height": 35,
			"seed": 957276616,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274098136,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 5",
			"rawText": "Layer 5",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 5"
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 409391304,
			"isDeleted": false,
			"id": "qJ7l3PA4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -613,
			"y": -200,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 110,
			"height": 35,
			"seed": 990959816,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274098136,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 4",
			"rawText": "Layer 4",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 4"
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 583106488,
			"isDeleted": false,
			"id": "frI3tePZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -613,
			"y": -140,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 111,
			"height": 35,
			"seed": 1827277256,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274098136,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 3",
			"rawText": "Layer 3",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 3"
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 65107912,
			"isDeleted": false,
			"id": "VDx0zwCK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -613,
			"y": -80,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 112,
			"height": 35,
			"seed": 970674376,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274098136,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 2",
			"rawText": "Layer 2",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 2"
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 1055443128,
			"isDeleted": false,
			"id": "FrLi6d5B",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -613,
			"y": -20,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 35,
			"seed": 46528456,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274098136,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 1",
			"rawText": "Layer 1",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 1"
		},
		{
			"type": "text",
			"version": 179,
			"versionNonce": 393166536,
			"isDeleted": false,
			"id": "q25nJtGC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -673,
			"y": 53,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 162,
			"height": 35,
			"seed": 326149576,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274098136,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Base Layer",
			"rawText": "Base Layer",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Base Layer"
		},
		{
			"type": "text",
			"version": 694,
			"versionNonce": 228117192,
			"isDeleted": false,
			"id": "MxfXIhjW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -460,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 1259,
			"height": 25,
			"seed": 1491598008,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670274254021,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Image can be build with reproducible methods using Dockerfile or store changes made on running container to obtain new image ",
			"rawText": "Image can be build with reproducible methods using Dockerfile or store changes made on running container to obtain new image ",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Image can be build with reproducible methods using Dockerfile or store changes made on running container to obtain new image "
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 1228831944,
			"isDeleted": false,
			"id": "3ZwT0cWB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1373,
			"y": -125,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 83,
			"height": 35,
			"seed": 915314376,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Image",
			"rawText": "Image",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Image"
		},
		{
			"type": "rectangle",
			"version": 197,
			"versionNonce": 1300927416,
			"isDeleted": false,
			"id": "V8lLAPVXlxPhzFbHgaJug",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633,
			"y": 55,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 80,
			"seed": 811669944,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 208,
			"versionNonce": 350462920,
			"isDeleted": false,
			"id": "2m6jw39f",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 853,
			"y": 80,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 167,
			"height": 35,
			"seed": 1428192712,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Base Image",
			"rawText": "Base Image",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Base Image"
		},
		{
			"type": "rectangle",
			"version": 228,
			"versionNonce": 1466916024,
			"isDeleted": false,
			"id": "vvV4r1Gb1XASH0WbkKkd8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633,
			"y": -5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1770332856,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 263,
			"versionNonce": 525069000,
			"isDeleted": false,
			"id": "7lbftrHc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 853,
			"y": 9,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 318,
			"height": 35,
			"seed": 920487112,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Update Package cache",
			"rawText": "Update Package cache",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Update Package cache"
		},
		{
			"type": "rectangle",
			"version": 241,
			"versionNonce": 1003685304,
			"isDeleted": false,
			"id": "EvijA8JSxaD1FWOVdMXQI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633,
			"y": -65,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1396706232,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 241,
			"versionNonce": 1662210504,
			"isDeleted": false,
			"id": "Zz_nUqjThbs659gKEVlGF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633,
			"y": -125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 157395912,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 241,
			"versionNonce": 131698360,
			"isDeleted": false,
			"id": "ZajwOI1J-16wIoU0sN71-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633,
			"y": -185,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 2008405176,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 241,
			"versionNonce": 659937480,
			"isDeleted": false,
			"id": "x1qwTl2HjAt-0E6WinMQx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633,
			"y": -245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 60,
			"seed": 1724445384,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 338,
			"versionNonce": 69662648,
			"isDeleted": false,
			"id": "3Bvns27c",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 673,
			"y": -54,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 597,
			"height": 35,
			"seed": 2089450936,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Install Software packages for app runtime",
			"rawText": "Install Software packages for app runtime",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Install Software packages for app runtime"
		},
		{
			"type": "text",
			"version": 430,
			"versionNonce": 1873772488,
			"isDeleted": false,
			"id": "hGkFwCh9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 666,
			"y": -115,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 557,
			"height": 35,
			"seed": 1169119688,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Copy custom config file for App run time",
			"rawText": "Copy custom config file for App run time",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Copy custom config file for App run time"
		},
		{
			"type": "text",
			"version": 505,
			"versionNonce": 1155481784,
			"isDeleted": false,
			"id": "esEvXHdI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 871,
			"y": -174,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 187,
			"height": 35,
			"seed": 853673656,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Add App code",
			"rawText": "Add App code",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Add App code"
		},
		{
			"type": "text",
			"version": 608,
			"versionNonce": 1815889608,
			"isDeleted": false,
			"id": "cXTO4K20",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 753,
			"y": -231,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 421,
			"height": 35,
			"seed": 1764810952,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Define initial processes to run",
			"rawText": "Define initial processes to run",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Define initial processes to run"
		},
		{
			"type": "line",
			"version": 99,
			"versionNonce": 967207352,
			"isDeleted": false,
			"id": "j8VNuQ-k8gisKLlzUIPAr",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 30,
			"angle": 0,
			"x": 1370.308552666327,
			"y": -61.02910402359623,
			"strokeColor": "#00000000",
			"backgroundColor": "#e67700",
			"width": 40,
			"height": 380,
			"seed": 660631480,
			"groupIds": [
				"qIuq64vEVVFeeTpWEOtbr"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0
				],
				[
					-1.1430204249753615,
					-0.10628442999907328
				],
				[
					-2.225198719169029,
					-0.42607512276248016
				],
				[
					-3.24829798204906,
					-0.9608889664027789
				],
				[
					-4.214020516550143,
					-1.712191717972555
				],
				[
					-5.124099023873654,
					-2.681449134524394
				],
				[
					-5.980296603487666,
					-3.8701610604841967
				],
				[
					-6.78431555832686,
					-5.279810296591207
				],
				[
					-7.537903788725963,
					-6.91184555621135
				],
				[
					-8.528856884580435,
					-9.626870753451938
				],
				[
					-9.3794155857233,
					-12.629576337792324
				],
				[
					-10.100082493296227,
					-15.85729267339117
				],
				[
					-10.701390606707605,
					-19.24729899334716
				],
				[
					-11.19388812449914,
					-22.736891574445647
				],
				[
					-11.588077647812518,
					-26.263366693471973
				],
				[
					-12.123664708638316,
					-33.176115565076195
				],
				[
					-12.286097846700777,
					-36.43699891491144
				],
				[
					-12.392354987918587,
					-39.48393286612925
				],
				[
					-12.45292353430007,
					-42.254213695514956
				],
				[
					-12.478366883520295,
					-44.68515472354058
				],
				[
					-12.479172437587607,
					-46.71403518330479
				],
				[
					-12.465903594177057,
					-48.27813430790628
				],
				[
					-12.449047755296988,
					-49.31478246150372
				],
				[
					-12.439168318622471,
					-49.761241833509125
				],
				[
					-12.439168318622471,
					-126.66498076199474
				],
				[
					-12.439168318622471,
					-126.66498076199474
				],
				[
					-12.551763498445318,
					-133.72092216705585
				],
				[
					-12.888834678646617,
					-140.3557907713886
				],
				[
					-13.449333119025553,
					-146.56454164374225
				],
				[
					-14.232255676781307,
					-152.34213837470932
				],
				[
					-15.236538412579712,
					-157.68353603303908
				],
				[
					-16.461147785353276,
					-162.5836982093241
				],
				[
					-17.905050254034506,
					-167.03758849415695
				],
				[
					-19.567197078422588,
					-171.0401619562869
				],
				[
					-20.797475727933993,
					-173.45235066806708
				],
				[
					-22.05860861813659,
					-175.54521738846697
				],
				[
					-23.335958983618745,
					-177.34134074138666
				],
				[
					-24.61492045723552,
					-178.86329935072632
				],
				[
					-25.880841074441932,
					-180.13366757946446
				],
				[
					-27.119099268959673,
					-181.17502831242282
				],
				[
					-28.315043076243796,
					-182.0099559125799
				],
				[
					-29.454081328282655,
					-182.66102900383586
				],
				[
					-30.52154686139795,
					-183.1508262100908
				],
				[
					-31.50281810931139,
					-183.5019261552449
				],
				[
					-32.38325830661137,
					-183.73690746319826
				],
				[
					-33.14826108615287,
					-183.87834023600772
				],
				[
					-33.78315928425761,
					-183.94881161941674
				],
				[
					-34.273346533780625,
					-183.9708959764038
				],
				[
					-34.60420126844366,
					-183.96716766994737
				],
				[
					-34.76105632456836,
					-183.96021384579092
				],
				[
					-35.301415913264634,
					-183.77369199992782
				],
				[
					-35.79882275112672,
					-183.3633652436373
				],
				[
					-36.24304782141323,
					-182.7545477125281
				],
				[
					-36.623877306515965,
					-181.972553542209
				],
				[
					-36.93105179142685,
					-181.04270539013203
				],
				[
					-37.15438785680439,
					-179.99030887006265
				],
				[
					-37.28362608764047,
					-178.84068237853123
				],
				[
					-37.30855266632696,
					-177.61914431206816
				],
				[
					-37.22550460172761,
					-176.4111602374199
				],
				[
					-37.04282621804904,
					-175.29819471588974
				],
				[
					-36.77167367916681,
					-174.30332063829098
				],
				[
					-36.42321834808979,
					-173.4496151563585
				],
				[
					-36.00863158782687,
					-172.7601596827488
				],
				[
					-35.539054363120215,
					-172.2580313691968
				],
				[
					-35.02568843524543,
					-171.96630310651574
				],
				[
					-34.47965956981133,
					-171.90805204644047
				],
				[
					-34.394802808343854,
					-171.92143560138865
				],
				[
					-34.174400175701976,
					-171.93041336333573
				],
				[
					-33.829866221028055,
					-171.91837199871188
				],
				[
					-33.37264589173125,
					-171.86871095671222
				],
				[
					-32.814184135220614,
					-171.7648211646886
				],
				[
					-32.1659106997719,
					-171.59009354999282
				],
				[
					-30.64570858169668,
					-170.96169282291362
				],
				[
					-28.903538320244976,
					-169.8506574988975
				],
				[
					-27.030883499022877,
					-168.12412351860226
				],
				[
					-25.119273299036486,
					-165.6492353445291
				],
				[
					-24.177443802154393,
					-164.0896357532053
				],
				[
					-23.26019130389185,
					-162.2931289173358
				],
				[
					-21.985667977211932,
					-159.2043953245893
				],
				[
					-20.88040219946658,
					-155.7178279978726
				],
				[
					-19.94462195765597,
					-151.83739811617698
				],
				[
					-19.17852484051359,
					-147.5670683366504
				],
				[
					-18.582323635906278,
					-142.91080983828422
				],
				[
					-18.156200733434176,
					-137.87258527822635
				],
				[
					-17.90038412009747,
					-132.45635731362478
				],
				[
					-17.815071384629647,
					-126.66609712347083
				],
				[
					-17.810086068892346,
					-50.1655862557827
				],
				[
					-17.810086068892346,
					-50.1655862557827
				],
				[
					-17.826151552838454,
					-49.5517067497361
				],
				[
					-17.848874257189856,
					-48.27312346402884
				],
				[
					-17.86509173246941,
					-46.39792592685951
				],
				[
					-17.861565533533273,
					-43.99420366642666
				],
				[
					-17.825102812637624,
					-41.12997803618224
				],
				[
					-17.742480323771936,
					-37.87335560801149
				],
				[
					-17.600490020059055,
					-34.29240886642631
				],
				[
					-17.385939053755152,
					-30.455176208565295
				],
				[
					-17.08560417884972,
					-26.429730118940377
				],
				[
					-16.68629254759894,
					-22.28417716943677
				],
				[
					-16.17478091399228,
					-18.08653871350642
				],
				[
					-15.537861231152597,
					-13.904921323034564
				],
				[
					-14.762325452202717,
					-9.807363395159792
				],
				[
					-13.834980729398808,
					-5.861954458080676
				],
				[
					-12.742588617597022,
					-2.1367669963091336
				],
				[
					-11.47197146818688,
					1.3001605930162405
				],
				[
					-10.302063776323472,
					3.835971425048319
				],
				[
					-9.045490626124497,
					6.018262108420878
				],
				[
					-10.302063776323472,
					8.220783647856443
				],
				[
					-11.47197146818688,
					10.754225407443062
				],
				[
					-12.742497422796951,
					14.194306078800164
				],
				[
					-13.83481353893201,
					17.921487651910684
				],
				[
					-14.762127863469225,
					21.86715224428967
				],
				[
					-15.537648443285761,
					25.962647886078827
				],
				[
					-16.174598524392138,
					30.13933965110654
				],
				[
					-16.686186153665517,
					34.3285755695145
				],
				[
					-17.085619377983065,
					38.46173775881777
				],
				[
					-17.3861214433553,
					42.47017424915804
				],
				[
					-17.60093079492607,
					46.28525011436369
				],
				[
					-17.74322508130586,
					49.83834747194976
				],
				[
					-17.82622754850518,
					53.06079730837129
				],
				[
					-17.86317664166789,
					55.88398174114333
				],
				[
					-17.86726520853781,
					58.23921471303427
				],
				[
					-17.851716495125444,
					60.05794651630575
				],
				[
					-17.829753747441316,
					61.27145700635289
				],
				[
					-17.81456981322924,
					61.81116238806402
				],
				[
					-17.81456981322924,
					138.71599211249574
				],
				[
					-17.81456981322924,
					138.71599211249574
				],
				[
					-17.899669760830236,
					144.48415516289765
				],
				[
					-18.15460482443291,
					149.88056131991598
				],
				[
					-18.57882783523683,
					154.90187002096584
				],
				[
					-19.17180682357491,
					159.54467252871558
				],
				[
					-19.932994620646724,
					163.80562828058027
				],
				[
					-20.86184405765183,
					167.68136262660164
				],
				[
					-21.957807965789783,
					171.1685009168214
				],
				[
					-23.220354375393505,
					174.26373667602786
				],
				[
					-24.129961709583313,
					176.05291472663444
				],
				[
					-25.067277063861816,
					177.60791252256058
				],
				[
					-26.977853722780722,
					180.081019631378
				],
				[
					-28.857712933208546,
					181.81408986550656
				],
				[
					-30.612468077070247,
					182.9381550879727
				],
				[
					-32.14771733715742,
					183.5843153365495
				],
				[
					-32.80352954274548,
					183.7691370746685
				],
				[
					-33.36908929452841,
					183.88360247426337
				],
				[
					-33.832571666763556,
					183.94414164927244
				],
				[
					-34.18218213197483,
					183.96708245151407
				],
				[
					-34.406126162686206,
					183.96885499492652
				],
				[
					-34.492609231421625,
					183.96578713132809
				],
				[
					-35.02132628397527,
					184.02434923868483
				],
				[
					-35.5253295457093,
					184.31678481436222
				],
				[
					-35.99171495241342,
					184.81970992026547
				],
				[
					-36.40759363901071,
					185.50970653092654
				],
				[
					-36.76007674042427,
					186.36339070825073
				],
				[
					-37.036244993310476,
					187.35734442676994
				],
				[
					-37.223194333459105,
					188.4681496610162
				],
				[
					-37.3080662940599,
					189.6724224728947
				],
				[
					-37.27990229997084,
					190.89288678709832
				],
				[
					-37.14870338093323,
					192.04190396683168
				],
				[
					-36.92451616408832,
					193.09407891897456
				],
				[
					-36.61740247571083,
					194.02415289989972
				],
				[
					-36.237393743808724,
					194.8067649038602
				],
				[
					-35.794551794656655,
					195.41662209985552
				],
				[
					-35.29892325539598,
					195.82843165688527
				],
				[
					-34.76055475316798,
					196.01683256920242
				],
				[
					-34.60859381798048,
					196.02296829639928
				],
				[
					-34.293394190663236,
					196.02910402359618
				],
				[
					-33.87775869019947,
					196.01662804496252
				],
				[
					-33.34866165931217,
					195.96904207181348
				],
				[
					-32.715952136409186,
					195.8711090482768
				],
				[
					-31.98952475729834,
					195.7076260058536
				],
				[
					-30.29501897801788,
					195.12312981560535
				],
				[
					-28.344119018333572,
					194.0938274909575
				],
				[
					-26.21584517250826,
					192.49792484705225
				],
				[
					-23.989187336538066,
					190.2137299611517
				],
				[
					-22.86364591490993,
					188.7754814188326
				],
				[
					-21.743150605552465,
					187.11948273577138
				],
				[
					-20.63755044687351,
					185.23053094346906
				],
				[
					-19.55674007468094,
					183.09342307342678
				],
				[
					-17.89190300369073,
					179.08894071839114
				],
				[
					-16.44743816707571,
					174.63348241438578
				],
				[
					-15.223847136236287,
					169.73222944215462
				],
				[
					-14.221616283439516,
					164.3902267329485
				],
				[
					-13.441231980952438,
					158.6126214801381
				],
				[
					-12.883195800175471,
					152.40449270234748
				],
				[
					-12.548024511642346,
					145.77095350557406
				],
				[
					-12.436189288486773,
					138.7171169958152
				],
				[
					-12.441660976491121,
					61.424679749408
				],
				[
					-12.441660976491121,
					61.424679749408
				],
				[
					-12.47839728178699,
					59.762477164403265
				],
				[
					-12.494432367466402,
					57.784148279266574
				],
				[
					-12.48443133772512,
					55.5291662722978
				],
				[
					-12.443013699358858,
					53.03700432179677
				],
				[
					-12.244467420467686,
					47.499203740263944
				],
				[
					-11.855901576492101,
					41.486685354246795
				],
				[
					-11.234409013998018,
					35.315422070697366
				],
				[
					-10.337097778684658,
					29.301352709194347
				],
				[
					-9.771598823435085,
					26.452006217402335
				],
				[
					-9.121060717117906,
					23.760450176689766
				],
				[
					-8.380102966528845,
					21.26617480904315
				],
				[
					-7.543390675863662,
					19.00867033644899
				],
				[
					-6.788905696597176,
					17.373311557930542
				],
				[
					-5.983762005890419,
					15.961190987258124
				],
				[
					-5.126348495608781,
					14.770689474199237
				],
				[
					-4.215008460217597,
					13.800221955894685
				],
				[
					-3.2481459907156065,
					13.048203369485268
				],
				[
					-2.2241043815681607,
					12.513014564738498
				],
				[
					-1.141257325507297,
					12.193070478795164
				],
				[
					0.0020062856015954367,
					12.086786048796093
				],
				[
					0.5466824281679479,
					11.964361247531933
				],
				[
					1.052767971170283,
					11.613210171317867
				],
				[
					1.509775512600271,
					11.05751781152156
				],
				[
					1.9072024513162305,
					10.321400984764033
				],
				[
					2.234576584443161,
					9.42906172609959
				],
				[
					2.4813953108393747,
					8.404633895835914
				],
				[
					2.6371864276298993,
					7.27230248534066
				],
				[
					2.6914473336730396,
					6.056235442294824
				],
				[
					2.6360312934956482,
					4.83488485638502
				],
				[
					2.4788418564373487,
					3.697678951505587
				],
				[
					2.230624809773346,
					2.6689049811441308
				],
				[
					1.9021107416455152,
					1.7727649803549639
				],
				[
					1.5040454393290545,
					1.033563246312342
				],
				[
					1.047174690099176,
					0.47553590144389624
				],
				[
					0.5422442812310919,
					0.12291906817724829
				],
				[
					0,
					0
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 197,
			"versionNonce": 1771580872,
			"isDeleted": false,
			"id": "wMHM4kJV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 500,
			"y": -225,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 109,
			"height": 35,
			"seed": 1357481928,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 5",
			"rawText": "Layer 5",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 5"
		},
		{
			"type": "text",
			"version": 206,
			"versionNonce": 1033925304,
			"isDeleted": false,
			"id": "kb4Ol6xl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 500,
			"y": -165,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 110,
			"height": 35,
			"seed": 841595064,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 4",
			"rawText": "Layer 4",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 4"
		},
		{
			"type": "text",
			"version": 193,
			"versionNonce": 1088369864,
			"isDeleted": false,
			"id": "yJR8P3JA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 500,
			"y": -105,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 111,
			"height": 35,
			"seed": 687165128,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 3",
			"rawText": "Layer 3",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 3"
		},
		{
			"type": "text",
			"version": 193,
			"versionNonce": 661740472,
			"isDeleted": false,
			"id": "3Bj9dEP6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 500,
			"y": -45,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 112,
			"height": 35,
			"seed": 115466680,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 2",
			"rawText": "Layer 2",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 2"
		},
		{
			"type": "text",
			"version": 193,
			"versionNonce": 1202543560,
			"isDeleted": false,
			"id": "vO2cusBw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 500,
			"y": 15,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 35,
			"seed": 972043720,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Layer 1",
			"rawText": "Layer 1",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Layer 1"
		},
		{
			"type": "text",
			"version": 217,
			"versionNonce": 1497179320,
			"isDeleted": false,
			"id": "t0BtGgEL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 440,
			"y": 88,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 162,
			"height": 35,
			"seed": 1152182968,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Base Layer",
			"rawText": "Base Layer",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Base Layer"
		},
		{
			"type": "rectangle",
			"version": 61,
			"versionNonce": 1075749576,
			"isDeleted": false,
			"id": "574zfFHhXeeQ10WPePKu9",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 620,
			"y": -265,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 700,
			"height": 420,
			"seed": 252958152,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276159761,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 424,
			"versionNonce": 1595827400,
			"isDeleted": false,
			"id": "NHtdzQdXCYw8ZOeaXyZtU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635,
			"y": -360,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 660,
			"height": 80,
			"seed": 1621073352,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"type": "text",
					"id": "9YOUBmKK"
				}
			],
			"updated": 1670276276835,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 374,
			"versionNonce": 978500536,
			"isDeleted": false,
			"id": "9YOUBmKK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 816.5,
			"y": -332.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 297,
			"height": 25,
			"seed": 822608568,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276299713,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Container (Process Execution)",
			"rawText": "Container (Process Execution)",
			"baseline": 18,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "NHtdzQdXCYw8ZOeaXyZtU",
			"originalText": "Container (Process Execution)"
		},
		{
			"type": "text",
			"version": 199,
			"versionNonce": 854780344,
			"isDeleted": false,
			"id": "G6g5DSvp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1386,
			"y": -87,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 171,
			"height": 25,
			"seed": 1655778744,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276339380,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Read only Layers",
			"rawText": "Read only Layers",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Read only Layers"
		},
		{
			"type": "text",
			"version": 232,
			"versionNonce": 72273608,
			"isDeleted": false,
			"id": "WRMWD45a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1320,
			"y": -360,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 254,
			"height": 35,
			"seed": 396221368,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276444671,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Read-write Layers",
			"rawText": "Read-write Layers",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Read-write Layers"
		},
		{
			"type": "text",
			"version": 303,
			"versionNonce": 1099776200,
			"isDeleted": false,
			"id": "lmyHtsPx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1340,
			"y": -320,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 450,
			"height": 50,
			"seed": 831182280,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1670276490990,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "All the contain will be removed after stopping\n     except those stored in Disk explicitly  ",
			"rawText": "All the contain will be removed after stopping\n     except those stored in Disk explicitly  ",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "All the contain will be removed after stopping\n     except those stored in Disk explicitly  "
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 135489855,
			"isDeleted": false,
			"id": "JaNh05eS",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -520,
			"y": -1540,
			"strokeColor": "#e67700",
			"backgroundColor": "#82c91e",
			"width": 208,
			"height": 25,
			"seed": 2073309009,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "What is a container?",
			"rawText": "What is a container?",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "What is a container?"
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 1143082545,
			"isDeleted": false,
			"id": "ikU3dEK7",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480,
			"y": -1500,
			"strokeColor": "#495057",
			"backgroundColor": "#82c91e",
			"width": 1259,
			"height": 75,
			"seed": 1518725695,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Simply put, a container is a sandboxed process on your machine that is isolated from all other processes on the host machine.\n That isolation leverages kernel namespaces and cgroups, features that have been in Linux for a long time.\n Docker has worked to make these capabilities approachable and easy to use. To summarize, a container:",
			"rawText": "Simply put, a container is a sandboxed process on your machine that is isolated from all other processes on the host machine.\n That isolation leverages kernel namespaces and cgroups, features that have been in Linux for a long time.\n Docker has worked to make these capabilities approachable and easy to use. To summarize, a container:",
			"baseline": 68,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Simply put, a container is a sandboxed process on your machine that is isolated from all other processes on the host machine.\n That isolation leverages kernel namespaces and cgroups, features that have been in Linux for a long time.\n Docker has worked to make these capabilities approachable and easy to use. To summarize, a container:"
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 292677983,
			"isDeleted": false,
			"id": "eq78FnbK",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -440,
			"y": -1365,
			"strokeColor": "#495057",
			"backgroundColor": "#82c91e",
			"width": 1238,
			"height": 25,
			"seed": 1758731569,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "* is a runnable instance of an image. You can create, start, stop, move, or delete a container using the DockerAPI or CLI.",
			"rawText": "* is a runnable instance of an image. You can create, start, stop, move, or delete a container using the DockerAPI or CLI.",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "* is a runnable instance of an image. You can create, start, stop, move, or delete a container using the DockerAPI or CLI."
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 1711480849,
			"isDeleted": false,
			"id": "ZQHl0dpT",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -440,
			"y": -1410,
			"strokeColor": "#495057",
			"backgroundColor": "#82c91e",
			"width": 733,
			"height": 25,
			"seed": 1407994463,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "* can be run on local machines, virtual machines or deployed to the cloud.",
			"rawText": "* can be run on local machines, virtual machines or deployed to the cloud.",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "* can be run on local machines, virtual machines or deployed to the cloud."
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 1196123519,
			"isDeleted": false,
			"id": "4kz5X8FA",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -440,
			"y": -1385,
			"strokeColor": "#495057",
			"backgroundColor": "#82c91e",
			"width": 371,
			"height": 25,
			"seed": 1738231569,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "* is portable (can be run on any OS).",
			"rawText": "* is portable (can be run on any OS).",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "* is portable (can be run on any OS)."
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 833025521,
			"isDeleted": false,
			"id": "SRB7Pgo0",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -440,
			"y": -1340,
			"strokeColor": "#495057",
			"backgroundColor": "#82c91e",
			"width": 907,
			"height": 25,
			"seed": 1842456191,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "* is isolated from other containers and runs its own software, binaries, and configurations.",
			"rawText": "* is isolated from other containers and runs its own software, binaries, and configurations.",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "* is isolated from other containers and runs its own software, binaries, and configurations."
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 1491099039,
			"isDeleted": false,
			"id": "wDgpFbo2",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -520,
			"y": -1301,
			"strokeColor": "#e67700",
			"backgroundColor": "#82c91e",
			"width": 269,
			"height": 25,
			"seed": 1314997489,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "What is a container image?",
			"rawText": "What is a container image?",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "What is a container image?"
		},
		{
			"type": "text",
			"version": 47,
			"versionNonce": 1779765201,
			"isDeleted": false,
			"id": "YbCs3Zdp",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -460,
			"y": -1261,
			"strokeColor": "#495057",
			"backgroundColor": "#82c91e",
			"width": 1257,
			"height": 100,
			"seed": 922123935,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "When running a container, it uses an isolated filesystem. This custom filesystem is provided by a container image. \nSince the image contains the container’s filesystem, it must contain everything needed to run an application - all dependencies,\n configurations, scripts, binaries, etc. The image also contains other configuration for the container, \nsuch as environment variables, a default command to run, and other metadata.",
			"rawText": "When running a container, it uses an isolated filesystem. This custom filesystem is provided by a container image. \nSince the image contains the container’s filesystem, it must contain everything needed to run an application - all dependencies,\n configurations, scripts, binaries, etc. The image also contains other configuration for the container, \nsuch as environment variables, a default command to run, and other metadata.",
			"baseline": 93,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "When running a container, it uses an isolated filesystem. This custom filesystem is provided by a container image. \nSince the image contains the container’s filesystem, it must contain everything needed to run an application - all dependencies,\n configurations, scripts, binaries, etc. The image also contains other configuration for the container, \nsuch as environment variables, a default command to run, and other metadata."
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 962679231,
			"isDeleted": false,
			"id": "MiXlaLXJ",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -420,
			"y": -1141,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 48,
			"height": 25,
			"seed": 950894289,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Note",
			"rawText": "Note",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Note"
		},
		{
			"type": "text",
			"version": 55,
			"versionNonce": 90500529,
			"isDeleted": false,
			"id": "fQG7biKQ",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -420,
			"y": -1101,
			"strokeColor": "#364fc7",
			"backgroundColor": "#82c91e",
			"width": 1108,
			"height": 40,
			"seed": 302731967,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057803704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "If you’re familiar with chroot, think of a container as an extended version of chroot. The filesystem is simply coming from the image. But, \na container adds additional isolation not available when simply using chroot.",
			"rawText": "If you’re familiar with chroot, think of a container as an extended version of chroot. The filesystem is simply coming from the image. But, \na container adds additional isolation not available when simply using chroot.",
			"baseline": 34,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If you’re familiar with chroot, think of a container as an extended version of chroot. The filesystem is simply coming from the image. But, \na container adds additional isolation not available when simply using chroot."
		},
		{
			"type": "text",
			"version": 153,
			"versionNonce": 1587808209,
			"isDeleted": false,
			"id": "mjFkEbkj",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 380,
			"y": -1020,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"width": 284,
			"height": 25,
			"seed": 343674161,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": null,
			"updated": 1671057866398,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Copied from Docker Web site",
			"rawText": "Copied from Docker Web site",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Copied from Docker Web site"
		},
		{
			"type": "rectangle",
			"version": 141,
			"versionNonce": 643024447,
			"isDeleted": true,
			"id": "AUasXnhGT7ia1J2Ah4Z5-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -520,
			"y": 960,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 100,
			"seed": 631752222,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897910,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 1851916593,
			"isDeleted": true,
			"id": "dXE45Wv8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -300,
			"y": 980,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 227,
			"height": 45,
			"seed": 313472478,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897910,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Linus Kernel ",
			"rawText": "Linus Kernel ",
			"baseline": 32,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linus Kernel "
		},
		{
			"type": "rectangle",
			"version": 172,
			"versionNonce": 1613850481,
			"isDeleted": true,
			"id": "FTXC6BBZN9Byf7ltK92aC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -520,
			"y": 860,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 100,
			"seed": 976014722,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 1238151953,
			"isDeleted": true,
			"id": "PbHALNxe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -300,
			"y": 880,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 207,
			"height": 45,
			"seed": 1710375838,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "JVtyMov0gHR4xk5vi2l9G",
					"type": "arrow"
				}
			],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "System Call",
			"rawText": "System Call",
			"baseline": 32,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "System Call"
		},
		{
			"type": "rectangle",
			"version": 79,
			"versionNonce": 215515775,
			"isDeleted": true,
			"id": "xk7QGhxU8L9FXPFzS8JaL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -420,
			"y": 620,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 440,
			"height": 80,
			"seed": 2000860610,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 203,
			"versionNonce": 751184113,
			"isDeleted": true,
			"id": "BD0IE36s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -300,
			"y": 645,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 189,
			"height": 35,
			"seed": 435782146,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Docker Engine",
			"rawText": "Docker Engine",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Docker Engine"
		},
		{
			"type": "ellipse",
			"version": 51,
			"versionNonce": 59753503,
			"isDeleted": true,
			"id": "jWsjcuDLiqTRzN_fpM-gk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -360,
			"y": 700,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 40,
			"seed": 943413250,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 70,
			"versionNonce": 1087759057,
			"isDeleted": true,
			"id": "rOxqnzlVCEqetw1bPGCU5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -60,
			"y": 700,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 40,
			"seed": 1780662146,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 68,
			"versionNonce": 290804049,
			"isDeleted": true,
			"id": "B4_kk2y1E7YbVPHoAuSJJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -140,
			"y": 700,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 40,
			"seed": 1309438366,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 57,
			"versionNonce": 1449125951,
			"isDeleted": true,
			"id": "6SG8Rn9Vd3jTJyEPgsbvn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260,
			"y": 700,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 40,
			"seed": 1013153602,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 231,
			"versionNonce": 458555103,
			"isDeleted": true,
			"id": "N7LUnL6dhOgKYQWH-vdCw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -340,
			"y": 740,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 120,
			"seed": 221756062,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jWsjcuDLiqTRzN_fpM-gk",
				"focus": 0,
				"gap": 1
			},
			"endBinding": {
				"elementId": "FTXC6BBZN9Byf7ltK92aC",
				"focus": -0.45454545454545453,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					120
				]
			]
		},
		{
			"type": "arrow",
			"version": 230,
			"versionNonce": 799416977,
			"isDeleted": true,
			"id": "1Q88O81KwbBmicnhbvDXO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -240,
			"y": 740,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 120,
			"seed": 566144030,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6SG8Rn9Vd3jTJyEPgsbvn",
				"focus": 0,
				"gap": 1
			},
			"endBinding": {
				"elementId": "FTXC6BBZN9Byf7ltK92aC",
				"focus": -0.15151515151515152,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					120
				]
			]
		},
		{
			"type": "arrow",
			"version": 231,
			"versionNonce": 523225855,
			"isDeleted": true,
			"id": "JVtyMov0gHR4xk5vi2l9G",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -120,
			"y": 740,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 120,
			"seed": 1319760770,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "B4_kk2y1E7YbVPHoAuSJJ",
				"focus": 0,
				"gap": 1
			},
			"endBinding": {
				"elementId": "FTXC6BBZN9Byf7ltK92aC",
				"focus": 0.21212121212121213,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					120
				]
			]
		},
		{
			"type": "arrow",
			"version": 152,
			"versionNonce": 80062577,
			"isDeleted": true,
			"id": "P99DsZLL7KbjntGn86xnf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -38.23745554755442,
			"y": 739.4232640006672,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 120,
			"seed": 298969602,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "FTXC6BBZN9Byf7ltK92aC",
				"focus": 0.4598864983407442,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					120
				]
			]
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 1377571615,
			"isDeleted": true,
			"id": "kYu2FcWT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 0,
			"y": 780,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 127,
			"height": 35,
			"seed": 1772142750,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Sys Call ",
			"rawText": "Sys Call ",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Sys Call "
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 2075750993,
			"isDeleted": true,
			"id": "zq4epEoyMZu12Pi06W7xe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380,
			"y": 800,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 360,
			"height": 0,
			"seed": 524956446,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					360,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 47,
			"versionNonce": 1284134719,
			"isDeleted": true,
			"id": "VqyC1kM6KE4N4uMRyPynn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -420,
			"y": 440,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 160,
			"seed": 1458136322,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 1499004977,
			"isDeleted": true,
			"id": "tJ8125tn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -400,
			"y": 460,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 76,
			"height": 105,
			"seed": 1344573790,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "APP\nMicr\n Fend",
			"rawText": "APP\nMicr\n Fend",
			"baseline": 95,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "APP\nMicr\n Fend"
		},
		{
			"type": "rectangle",
			"version": 59,
			"versionNonce": 1155209055,
			"isDeleted": true,
			"id": "6WyZo7hli--KZhIlaV8qp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -280,
			"y": 440,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 160,
			"seed": 1770797826,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 1535889937,
			"isDeleted": true,
			"id": "PUdGfABf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260,
			"y": 480,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 77,
			"height": 70,
			"seed": 1890217502,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "APP\nProxy",
			"rawText": "APP\nProxy",
			"baseline": 60,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "APP\nProxy"
		},
		{
			"type": "rectangle",
			"version": 67,
			"versionNonce": 1365169023,
			"isDeleted": true,
			"id": "o2Pwmcx_tIs-JDBg8Ei4d",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -140,
			"y": 440,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 160,
			"seed": 848567646,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 390686705,
			"isDeleted": true,
			"id": "1Af4uMj7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -120,
			"y": 480,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 56,
			"height": 70,
			"seed": 105738114,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "APP\nDB",
			"rawText": "APP\nDB",
			"baseline": 60,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "APP\nDB"
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 1784023967,
			"isDeleted": true,
			"id": "gmqTDO75",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2.25,
			"y": 521.2421875,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 56,
			"height": 35,
			"seed": 1872011230,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": ".......",
			"rawText": ".......",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "......."
		},
		{
			"type": "rectangle",
			"version": 54,
			"versionNonce": 379142609,
			"isDeleted": true,
			"id": "TMOboasURLBLwHJ7zRo6j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -500,
			"y": 380,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 540,
			"height": 40,
			"seed": 1746442754,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 737230783,
			"isDeleted": true,
			"id": "dztua2Hv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380,
			"y": 380,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 250,
			"height": 35,
			"seed": 769446302,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Docker Toolchains",
			"rawText": "Docker Toolchains",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Docker Toolchains"
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 915595185,
			"isDeleted": true,
			"id": "w6fpan4c",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 120,
			"y": 620,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 222,
			"height": 35,
			"seed": 693706690,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Software layer ",
			"rawText": "Software layer ",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Software layer "
		},
		{
			"type": "text",
			"version": 150,
			"versionNonce": 1481699295,
			"isDeleted": true,
			"id": "ragBrAd9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 240,
			"y": 860,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 344,
			"height": 35,
			"seed": 846949058,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Linux Kernel main Stream",
			"rawText": "Linux Kernel main Stream",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux Kernel main Stream"
		},
		{
			"type": "line",
			"version": 66,
			"versionNonce": 1163772305,
			"isDeleted": true,
			"id": "H2sUTtKvkmnYPaoKRZijN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 180,
			"y": 860,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 200,
			"seed": 1892745730,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					40,
					100
				],
				[
					20,
					200
				]
			]
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 428186623,
			"isDeleted": true,
			"id": "1pWk4Di8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 245.75,
			"y": 910.2421875,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 156,
			"height": 70,
			"seed": 1065723202,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057897911,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "cgroup (V2)\nNamespace",
			"rawText": "cgroup (V2)\nNamespace",
			"baseline": 60,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "cgroup (V2)\nNamespace"
		},
		{
			"type": "rectangle",
			"version": 193,
			"versionNonce": 13269521,
			"isDeleted": true,
			"id": "aS28ka111jqrpDob5LoDb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 120,
			"y": 640,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 100,
			"seed": 788165832,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 214,
			"versionNonce": 582921087,
			"isDeleted": true,
			"id": "Gf6RDTtB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 240,
			"y": 660,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 439,
			"height": 45,
			"seed": 732568504,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Operating System (Linux)",
			"rawText": "Operating System (Linux)",
			"baseline": 32,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Operating System (Linux)"
		},
		{
			"type": "rectangle",
			"version": 231,
			"versionNonce": 1853034481,
			"isDeleted": true,
			"id": "VmsYHrfGEPwlBUzwBo3As",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 120,
			"y": 540,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 660,
			"height": 100,
			"seed": 1348508616,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 280,
			"versionNonce": 838525855,
			"isDeleted": true,
			"id": "ejvgkRP0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 270,
			"y": 565,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 335,
			"height": 45,
			"seed": 1482548408,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Container Run time",
			"rawText": "Container Run time",
			"baseline": 32,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Container Run time"
		},
		{
			"type": "rectangle",
			"version": 136,
			"versionNonce": 709749201,
			"isDeleted": true,
			"id": "L8S1mjL7Tz7zVvGE8Mcek",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 120,
			"y": 480,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 60,
			"seed": 824388808,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 158,
			"versionNonce": 1497044927,
			"isDeleted": true,
			"id": "Z2aMz7z2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 140,
			"y": 500,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 17,
			"height": 20,
			"seed": 1200153528,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C1",
			"rawText": "C1",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C1"
		},
		{
			"type": "text",
			"version": 151,
			"versionNonce": 1030916017,
			"isDeleted": true,
			"id": "BGqNSVuX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 400,
			"y": 500,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 33,
			"height": 20,
			"seed": 1719489976,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": ".......",
			"rawText": ".......",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "......."
		},
		{
			"type": "text",
			"version": 209,
			"versionNonce": 1855965151,
			"isDeleted": true,
			"id": "dBr3toCG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 820,
			"y": 640,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 344,
			"height": 35,
			"seed": 636195000,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Linux Kernel main Stream",
			"rawText": "Linux Kernel main Stream",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux Kernel main Stream"
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 570976657,
			"isDeleted": true,
			"id": "T9J1QCfg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 800,
			"y": 780,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 228,
			"height": 35,
			"seed": 1420343736,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Server Hardware",
			"rawText": "Server Hardware",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Server Hardware"
		},
		{
			"type": "rectangle",
			"version": 221,
			"versionNonce": 809071615,
			"isDeleted": true,
			"id": "0zhE6ZIqsS8T6nIZRel7O",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 580,
			"y": 780,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 165.65217391304327,
			"height": 45.65217391304343,
			"seed": 580943544,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 370,
			"versionNonce": 558305137,
			"isDeleted": true,
			"id": "iCsBemaQGpFtU62byXcBP",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 617.6086956521738,
			"y": 826.4347826086957,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.217391304347874,
			"height": 12.173913043478212,
			"seed": 884336840,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 440,
			"versionNonce": 1174969375,
			"isDeleted": true,
			"id": "KmCYqF39hwojcq1-GJWLN",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 650,
			"y": 825.7826086956521,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.217391304347874,
			"height": 12.608695652173868,
			"seed": 143648696,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 411,
			"versionNonce": 1903556945,
			"isDeleted": true,
			"id": "WS1xtFZ8uEobsKZXXuXPe",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 683.0434782608695,
			"y": 827.217391304348,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 51.30434782608702,
			"height": 11.304347826086898,
			"seed": 1988988872,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 470,
			"versionNonce": 66961471,
			"isDeleted": true,
			"id": "kTavisTDjhkgaDNySiAk0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 587.3913043478262,
			"y": 786.5217391304348,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 782905528,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 491,
			"versionNonce": 334276401,
			"isDeleted": true,
			"id": "fEVfcxOEFsEotpG0iq3Wq",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 619.1304347826087,
			"y": 786.304347826087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 215504584,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 489,
			"versionNonce": 1811505247,
			"isDeleted": true,
			"id": "2OEckfVcnloxdct7Fv8Ay",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 651.304347826087,
			"y": 786.7391304347826,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 210983352,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 498,
			"versionNonce": 1930598673,
			"isDeleted": true,
			"id": "VcsdFyTqaDUXZi4xFckRQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 683.478260869565,
			"y": 787.1739130434783,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 1009925576,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 487,
			"versionNonce": 1875639423,
			"isDeleted": true,
			"id": "LRPFLHVqeO9WzhdbzijG7",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 712.1739130434783,
			"y": 787.1739130434783,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 91185848,
			"groupIds": [
				"WWZcmBQm5n0iJBSZtwTAj"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 269,
			"versionNonce": 1079987953,
			"isDeleted": true,
			"id": "ypXTHXD5seHLmb2huycAw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 485.5673388302132,
			"y": 786.3184558163397,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 48.58791843016536,
			"height": 45.695780428369815,
			"seed": 1768159416,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 262,
			"versionNonce": 1932924063,
			"isDeleted": true,
			"id": "DmY-fictETWbF5dxSjQdj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 495.4006080363172,
			"y": 760.2892138001797,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1233063624,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 296,
			"versionNonce": 307906769,
			"isDeleted": true,
			"id": "2zhdsLxC_h_yYu1IlYcX_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 508.12601524421757,
			"y": 760,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1557406136,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 302,
			"versionNonce": 233318591,
			"isDeleted": true,
			"id": "LRBhOqoXrRXcy7fj8O1y5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 519.6945672514005,
			"y": 760.5784276003591,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 591525320,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 292,
			"versionNonce": 1117456049,
			"isDeleted": true,
			"id": "8lPUcpv4oh2R5rOxPnXLL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 495.4006080363172,
			"y": 831.7250224445299,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 576137912,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 326,
			"versionNonce": 226670815,
			"isDeleted": true,
			"id": "qgJPOl0INmIXXbS75PYiK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 508.1260152442171,
			"y": 831.4358086443503,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 839908552,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 332,
			"versionNonce": 197724305,
			"isDeleted": true,
			"id": "07PhuLQV4euouAfzxcVMR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 519.6945672513987,
			"y": 832.0142362447095,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 881923000,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 355,
			"versionNonce": 932594943,
			"isDeleted": true,
			"id": "T6R1vgxzBjuohcsycPAD2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 471.65051103801784,
			"y": 806.8353866839728,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1736778696,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 389,
			"versionNonce": 1738264177,
			"isDeleted": true,
			"id": "Kh-94uCDj2aUckkj0eACk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 470.7914968260018,
			"y": 794.1357123648166,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 430300344,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 395,
			"versionNonce": 1268993311,
			"isDeleted": true,
			"id": "vAOJwrbTKD0zGoWKvX8Ie",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 470.8510793392327,
			"y": 782.5528619403372,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 566061768,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 382,
			"versionNonce": 752539729,
			"isDeleted": true,
			"id": "fObCVNy4nNn-pIZ002hNO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 542.6827507714127,
			"y": 810.3174839955191,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1933149624,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 416,
			"versionNonce": 1159352639,
			"isDeleted": true,
			"id": "VtnllHR9ZTjSKumOxS3LB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 541.823736559398,
			"y": 797.6178096763629,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 458543560,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 422,
			"versionNonce": 1834853937,
			"isDeleted": true,
			"id": "xfK4ceTZZuqLH8-CTO1Ch",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 541.8833190726289,
			"y": 786.0349592518835,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 242224824,
			"groupIds": [
				"O5QTBeS2jQ3GdSTjD7KDK"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 297,
			"versionNonce": 1566298463,
			"isDeleted": true,
			"id": "XCYBzFU8ngorrqsV0xTLj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 365.56733883021275,
			"y": 786.3184558163397,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 48.58791843016536,
			"height": 45.695780428369815,
			"seed": 2015887544,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 290,
			"versionNonce": 336312337,
			"isDeleted": true,
			"id": "6vPdcLvJLTNSf4YYc8Hlr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 375.4006080363167,
			"y": 760.2892138001797,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 2128578248,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 324,
			"versionNonce": 1303924095,
			"isDeleted": true,
			"id": "pfgrfbZr04niBsId0VFmr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 388.1260152442171,
			"y": 760,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 97987000,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 330,
			"versionNonce": 1121750513,
			"isDeleted": true,
			"id": "893SeuVmLvW5LZq_ve4ZA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 399.69456725140003,
			"y": 760.5784276003591,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1171484104,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 320,
			"versionNonce": 1366312351,
			"isDeleted": true,
			"id": "pFOXk6QGFAD6IPQA6KARx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 375.4006080363167,
			"y": 831.7250224445299,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1169765048,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 354,
			"versionNonce": 1893181393,
			"isDeleted": true,
			"id": "2JlpkBWVObniTBYQwYZKd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 388.1260152442171,
			"y": 831.4358086443503,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1941075144,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 360,
			"versionNonce": 1739864511,
			"isDeleted": true,
			"id": "QsHkidy37pIpxsHJ80MEi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 399.6945672513982,
			"y": 832.0142362447095,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 779230136,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 383,
			"versionNonce": 1209304497,
			"isDeleted": true,
			"id": "dx9jcnGU5jklLi1JPb4wy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 351.6505110380174,
			"y": 806.8353866839728,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1041800136,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 417,
			"versionNonce": 1436854751,
			"isDeleted": true,
			"id": "XXZA__bfSVZ-KTyu2Nb4E",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 350.7914968260018,
			"y": 794.1357123648166,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1109779640,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 423,
			"versionNonce": 1136306065,
			"isDeleted": true,
			"id": "ulrwLPM1Q4CMun2xWgLM-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 350.85107933923223,
			"y": 782.5528619403372,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 1193403080,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 410,
			"versionNonce": 1750210047,
			"isDeleted": true,
			"id": "Y7GADSK0dLt-r1aF4GWfz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 422.6827507714122,
			"y": 810.3174839955191,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 511217080,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 444,
			"versionNonce": 234982769,
			"isDeleted": true,
			"id": "Ne61k-eavcAtwGselSB7O",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 421.8237365593975,
			"y": 797.6178096763629,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 225069512,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 450,
			"versionNonce": 1992097311,
			"isDeleted": true,
			"id": "lzeQpvq-H12KoreeQKU2r",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.667574567837693,
			"x": 421.88331907262886,
			"y": 786.0349592518835,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 4.627420802872936,
			"height": 26.02924201616004,
			"seed": 210638520,
			"groupIds": [
				"vTC8nrThu6ZBUKAi7Oiia"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 237,
			"versionNonce": 506509137,
			"isDeleted": true,
			"id": "MQS2xfDDwtExZ-qwxzliZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 140,
			"y": 780,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 165.65217391304327,
			"height": 45.65217391304343,
			"seed": 1566694344,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 386,
			"versionNonce": 601219647,
			"isDeleted": true,
			"id": "4xwGaZdqYkVqJxK9svE0u",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 177.608695652174,
			"y": 826.4347826086957,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.217391304347874,
			"height": 12.173913043478212,
			"seed": 118531256,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 456,
			"versionNonce": 379561265,
			"isDeleted": true,
			"id": "njw5iCzotnjvEW7MeQS1g",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 210,
			"y": 825.7826086956521,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.217391304347874,
			"height": 12.608695652173868,
			"seed": 725820104,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 427,
			"versionNonce": 1618821727,
			"isDeleted": true,
			"id": "WqnmQ_heP9207duvhl9sz",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 243.0434782608695,
			"y": 827.217391304348,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 51.30434782608702,
			"height": 11.304347826086898,
			"seed": 2014006712,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 486,
			"versionNonce": 1656084241,
			"isDeleted": true,
			"id": "rdFS4ySSMY-thVkgrWbUy",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 147.391304347826,
			"y": 786.5217391304348,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 1533249992,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 507,
			"versionNonce": 763600511,
			"isDeleted": true,
			"id": "26l91VSfj3bzb4ObsxXq5",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 179.13043478260897,
			"y": 786.304347826087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 633919160,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 505,
			"versionNonce": 350932209,
			"isDeleted": true,
			"id": "x0xfORWEdc9IeJlXSVX7K",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 211.304347826087,
			"y": 786.7391304347826,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 417272008,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918598,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 514,
			"versionNonce": 497645215,
			"isDeleted": true,
			"id": "wFn5Y0LvHuZJcvI_rslmY",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 243.47826086956502,
			"y": 787.1739130434783,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 887963576,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 503,
			"versionNonce": 80086737,
			"isDeleted": true,
			"id": "jhpbzo0W19wKZ6GWissKK",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 272.173913043478,
			"y": 787.1739130434783,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.391304347826132,
			"height": 28.26086956521733,
			"seed": 1263646664,
			"groupIds": [
				"Vgcj63fitnFQkM6Xv9H0n"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 331,
			"versionNonce": 396315327,
			"isDeleted": true,
			"id": "1q9SDvF5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 280,
			"y": 860,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 343,
			"height": 20,
			"seed": 2137067976,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Hardware (CPU, Memory, Disk I/O Network)",
			"rawText": "Hardware (CPU, Memory, Disk I/O Network)",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Hardware (CPU, Memory, Disk I/O Network)"
		},
		{
			"type": "rectangle",
			"version": 173,
			"versionNonce": 752813233,
			"isDeleted": true,
			"id": "7R2P0jLs_lzvsN9du0-uB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 320,
			"y": 480,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 60,
			"seed": 619614920,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 149,
			"versionNonce": 1476762335,
			"isDeleted": true,
			"id": "RdPjewl5h17oN645rFm1I",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 184,
			"y": 480,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 60,
			"seed": 1847654856,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 191,
			"versionNonce": 1222461073,
			"isDeleted": true,
			"id": "A5jxR1eNA8B6dUvIM3WVX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249,
			"y": 480,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 60,
			"seed": 1004168888,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 158,
			"versionNonce": 862775039,
			"isDeleted": true,
			"id": "Dfn5wT3KEAwb1_GtL85qb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 720,
			"y": 480,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 60,
			"seed": 1382973640,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 163,
			"versionNonce": 863521905,
			"isDeleted": true,
			"id": "DziCXqHE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 200,
			"y": 500,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 20,
			"seed": 217564856,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C2",
			"rawText": "C2",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C2"
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 408268575,
			"isDeleted": true,
			"id": "xuMcH2TB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260,
			"y": 500,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 20,
			"seed": 260804296,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C3",
			"rawText": "C3",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C3"
		},
		{
			"type": "text",
			"version": 167,
			"versionNonce": 74946129,
			"isDeleted": true,
			"id": "fMPwjI3y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 340,
			"y": 500,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 20,
			"seed": 810638520,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C4",
			"rawText": "C4",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C4"
		},
		{
			"type": "text",
			"version": 217,
			"versionNonce": 1362129727,
			"isDeleted": true,
			"id": "jToXpE83",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 737,
			"y": 500,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 33,
			"height": 20,
			"seed": 878110392,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671057918599,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C...n",
			"rawText": "C...n",
			"baseline": 14,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C...n"
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#5c940d",
		"currentItemBackgroundColor": "#82c91e",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 4,
		"currentItemStrokeStyle": "dashed",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStrokeSharpness": "sharp",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 830.3333333333342,
		"scrollY": 1794.3333333333328,
		"zoom": {
			"value": 0.49999999999999994
		},
		"currentItemLinearStrokeSharpness": "round",
		"gridSize": 20,
		"colorPalette": {}
	},
	"files": {}
}
```
%%