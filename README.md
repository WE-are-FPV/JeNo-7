[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
> [!NOTE]
> Current version : **1.1.1** (read [changelog](#changelog) for details)

<!--![JeNo - Front view](./images/JeNo7_CloseProfileHeader.jpg)-->

# JeNo 7"
***7" drone FPV frame compatible with Air Unit O3 and O4 Pro, designed for LR, Cinematic, Freeride and even Freestyle. Many customizable options available.***

> [!NOTE]
> Designed in France by members of the [WE are FPV](https://www.wearefpv.fr/) community. The French version of the project is available on [Printables](https://www.printables.com/fr/model/847975-jeno-7-drone-frame). Note that a [2.5" version](https://github.com/WE-are-FPV/JeNo-Pocket), [3-3.5" version](https://github.com/WE-are-FPV/JeNo-3-3.5) and a [5.1-6" version](https://github.com/WE-are-FPV/JeNo-5.1) of the JeNo exist.

![JeNo classic - 3D render](./images/JeNo7_Profile_Render.jpg)

## Table of contents

* [Key features](#key-features)
* [Presentation](#presentation)
* [Detailed specifications](#detailed-specifications)
* [Versions and files](#versions-and-files)
* [Customization](#customization)
* [Cut it !](#cut-it-)
* [Bill of materials](#bill-of-materials)
* [Building/Assembly guide](#buildingassembly-guide)
* [Inspiration](#inspiration)
* [Tuning, Betaflight Preset ?](#tuning-betaflight-preset-)
* [Blackbox](#blackbox)
* [Videos](#videos)
* [Builds examples](#builds-examples)
* [Authors](#authors)
* [TPU](#tpu)
* [Community (remixes and TPU)](#community-remixes-and-tpu)
* [Changelog](#changelog)

## Key features
- [x] **Sturdiness** and **rigidity** (6 or 8 mm arms)
- [x] Designed as a **real 7"**, not 5" conversion
- [x] Excellent flight **performances**, easy to tune
- [x] **Wide-X** geometry
- [x] Perfect DJI **Air Unit O3 or O4 Pro** camera integration
- [x] Designed for : DJI Vista/AU O3/AU O4 Pro, WalkSnail, HDZero, Analogic
- [x] **Frame and standoffs NOT visible** in video feed, with any FPV camera
- [x] Stack **decoupled** from the arms
- [x] **Easy maintenance** : remove 3 screws to replace an arm
- [x] **Roomy** (30 mm high)
- [x] **Customizable** (arms thickness, camera plates)

## Presentation
Building on the success of the [5.1-6" version](https://github.com/WE-are-FPV/JeNo-5.1) and [3-3.5" version](https://github.com/WE-are-FPV/JeNo-3-3.5) versions, the **JeNo lineup** expands with this new variation in **7-8"**. We stay true to the JeNo spirit, offering a **versatile frame** that is perfect for **Long Range, cinematic**, and even **Freestyle** use, thanks to its strength and flight performance.

Given the limited options in the **Open Source** community for 7", especially for DJI O3/O4 Pro setups, we wanted to provide the community with a solid new option that caters to various needs while remaining true to the **"JeNo philosophy"** :

* **Clean Black Box** for easy tuning
* **Modularity**, with **8mm arms** (or 6mm with reinforcements) and a wide range of camera plates:
  - Classic at 25°
  - High tilt at 40°
  - Cinematic with clean FOV ("Wide") / 25° tilt (hard or soft)
  - Cinematic with clean FOV ("Wide") / 40° tilt
* Frame and standoffs invisible in the video feed with all cameras
* **100% clear FOV** with DJI O3/O4 Pro setups with cinematic camera plates (no frame or propellers visible)
* **Wide X** geometry for better flight feel
* Comfortable body for lipos up to over 6S / 3000mAh (+140mm available)

![JeNo 7 Profile](./images/JeNo7_Profile.jpg)

Finally, since this frame was designed by members of the [WE are FPV](https://www.wearefpv.fr/) **community**,  the "WaF" logo is engraved under the bottom plate (feel free to keep it or not). Join us on the WAF forum in [the official JeNo 7" thread](https://forum.wearefpv.fr/topic/22687-jeno-7/) to discuss it further.

![WE are FPV banner](./images/WAF_Banner.jpg)

The JeNo is also available in [2.5" version](https://github.com/WE-are-FPV/JeNo-Pocket), [3" and 3.5" version](https://github.com/WE-are-FPV/JeNo-3-3.5) and [5.1" and 6" version](https://github.com/WE-are-FPV/JeNo-5.1).

## Detailed specifications

||| 
| :--- | :--- |
| **Geometry** | **Wide-X** | 
| **Props size** | 7" | 
| **Weight** | **248 to 260 g** depending on the versions, including screws | 
| **Arms** | **6 mm** (with 4mm reinforcements), **8mm** | 
| **Body height** | 30 mm | 
| **Stack height** | 19.5 to 21.5 mm depending the arms heights | 
| **Bottom plate** | 3mm | 
| **Middle plate** | 2.5 mm | 
| **Top plate** | 2.5 mm | 
| **Camera plates** | 3 mm | 
| **Motors mounting** | 16 to 19 mm | 
| **Camera** | 20 mm (DJI), Micro, Nano. **Clear FOV**. Ajustable.
| **Main stack** | 30 mm x 30 mm (M3) and 20 mm x 20 mm (M3) stack | 
| **Back stack** | 20 mm x 20 mm and 25 .5 x 25.5 mm | 
| **Supported VTX** | Analogic, DJI Vista, DJI Air Unit O3/O4 Pro, WalkSnail, HDZero… | 
| **Strap passage** | Yes | 

## Versions and files

### Versioning
You will find the **current version** of the frame at the beginning of the description and the full [history of modifications](#changelog) at the end of the page.

We strongly recommend always cutting the latest version to ensure you benefit from the most recent optimizations.

The version **number format** is as follows :
```
<Major versions>.<Minor version>.<Revision>
ex : 1.3.2
```

* **Revision :** This number is incremented in the case of minor modifications with no significant impact.
* **Minor version :** This number is incremented for minor modifications that may potentially break compatibility with certain TPU parts.
* **Major version :** This number is incremented for significant modifications that break compatibility at the carbon level.

Since the creation of the JeNo 7", we have always strived to **maintain compatibility at the carbon level**. As a result, the version remains “1.x.y.”

In practical terms, this means that if you have the very first version of the JeNo 7" and want to equip it with the **O4 Pro**, you only need to have new camera plates cut—they will be compatible with your frame version!

**Note :** If you develop TPU parts for the JeNo, be sure to specify the version they are compatible with.

### Files management
To simplify things, we have reorganized the file structure. The files are now divided into **five groups** :

* **01-FRAME :** Contains **models** describing the **frame** in DXF, STEP, and STL formats for the current version. Also contains a PDF file which is a reformatted version of the DXF.
* **02-TPU :** Contains **TPU models** for the current frame version in STL format.
* **03-FRAME-HISTORY :** Contains previous versions of the frame.
* **04-TPU-HISTORY :** Contains TPU models that are no longer compatible with the current version.
* **OTHER-FILES :** Contains documentation files. No assembly manual at the moment, but can check the [assembly guide of the JeNo 5"](https://github.com/WE-are-FPV/JeNo-5.1/tree/main/OTHER-FILES) which is very similar.

The major change is that all options are now consolidated into a single file. This will make version management significantly easier for us.

If you want to view the DXF file with all annotations, we recommend using the free software [DWG TrueView](https://www.autodesk.com/products/dwg-trueview/overview). If you prefer not to use it, the PDF version of the file will contain all the necessary information.

## Customization
As usual, this JeNo is **customizable** : it offers several **options** to best adapt to different needs and preferences.

### The arms
> [!TIP]
> We **strongly recommend** having the version with **8mm** arms cut (see Black Box a little further down). 

However, the version with 6mm + reinforcements remains entirely viable in case you have constraints on the availability of 8mm carbon.

The weight of the two versions remains very similar.

![JeNo 7 weights](./images/JeNo7_Weights_6mmVS8mm.jpg)

![JeNo 7 verions](./images/JeNo7_NakedFrame.jpg)

### Camera plates and O3 integration

![JeNo 7 Cmera Plates](./images/JeNo7_InHand.jpg)

> [!CAUTION]
> The use of a 200mm coaxial cable for the O3 camera is mandatory.

Remarks regarding the **PWM frequency** of ESCs:

* **DJI recommends** using a PWM frequency of **48 kHz** or higher for effective stabilization
* However, a PWM frequency of **24 kHz is generally recommended for 7"**
* We have not observed stabilization issues while remaining at 24 kHz, even with a "hard mounted" camera. Therefore, we encourage you to test 24 kHz before anything higher.

Comparison of **FOV settings** with specific 7" Cinematic camera plates (Ultra Wide vs Wide):

![JeNo 7 Camera Plates](./images/JeNo7_FOV.jpg)

The "cinematic" camera plates will allow you to enjoy a completely clear FOV (set as **Wide** in the O3) (and consequently, after stabilization).

Several types of camera plates are available, so you will need to **choose** the type of camera plate that best suits **your needs**.

![JeNo 7 Camera Plates blue prints](./images/JeNo7_Camera_Plates.jpg)

## Cut it !
Unlike the 3 and 5" JeNos, the JeNo 7" won't be available in shop.

However, the JeNo 7" is available from [CNC Madness](https://cncdrones.com/jeno-7-inch.html) (Canada).

The ["01-FRAME"](https://github.com/WE-are-FPV/JeNo-7/tree/main/01-FRAME) folder contains all the files you need to get it **cut** in your favourite flavour.

Consult the **DXF file** of the frame (or the PDF version) to choose the version that interests you.

Feel free to select a pre-made "Edition" (Classic, Light, or Bando), or mix different options and choose certain "extras".

You will also need to choose a type of camera plates (classic, cine, etc.).

> [!NOTE]
> All parts versions are compatible with each others

## Bill of materials

In addition to the carbon fiber, you will need the following hardware to complete the assembly of the frame.

**Standoffs**

It is recommended to use 5mm diameter standoffs, especially for those that will serve as support for TPU (backpack and capacitor). Moletted spacers can still be used, but the TPU supports will need to be modified accordingly.

| Quantity | Description | Details |
| :---: | :--- | :--- |
| 10 | M3x30mm standoffs | for the body |
| 2 (or 4 for cinematic plates) | M3x20mm standoffs | for the camera |

**Stack materials**

* If 30x30 stack

| Quantity | Description | Details |
| :---: | :--- | :--- |
| 4 | M3x20mm countersunk screws | for the stack |
| 4 | M3 nuts for stack screws | |

* If 20x20 stack

| Quantity | Description | Details |
| :---: | :--- | :--- |
| 4 | M3x20mm countersunk screws | for the stack |
| 4 | M3 nuts for stack screws | |

**Frame materials**

| Quantity | Description | Details |
| :---: | :--- | :--- |
| 6 | M3x6/8mm countersunk screws | for the top plate |
| 4 | M3x6/8mm screws | for the top plate |
| 10 | M3x8mm screws (titanium if possible) | Bottom plate |
| 4 (or 8 for cinematic plates) | M3x6/8mm screws (titanium if possible) | Camera plates |
| 12 | Pressnuts ([Flywoo](https://www.drone-fpv-racer.com/flywoo-m3-clinch-nuts-20-pcs-7965.html?aff=64&id_campaign=13#/1063-couleur-titane) or SourceOne alike) | |
| 4 | M3x18mm countersunk screws + washers or M3x16mm screws (steel if possible)  | for the arms (2 mm shorter for 6mm arms) |
| 4 | M3x12mm countersunk screws + washers or M3x10mm screws (steel if possible) | for the arms (2 mm shorter for 6mm arms) |

**Additional materials 6mm amrs  renforcements**

| Quantity | Description | Details |
| :---: | :--- | :--- |
| 8 | Pressnuts ([Flywoo](https://www.drone-fpv-racer.com/flywoo-m3-clinch-nuts-20-pcs-7965.html?aff=64&id_campaign=13#/1063-couleur-titane) or SourceOne alike) | 2 per arm) |
| 8 | M3x12mm screws | 2 per arm |

**Additional materials**

| Quantity | Description | Details |
| :---: | :--- | :--- |
| 16 | M3x12mm screws (if using arms protections) or M3x8mm (if no TPU) | for the motors (2 mm shorter for 6mm arms) |
| 4 | M2x5mm screws | for the camera |

**Fasten the lipo**

The JeNo allows the use of non-slip straps thanks to its strap slots. You can also use a LiPo pad if desired.

## Building/Assembly guide

Find numerous examples of builds on the _**DroneBuilds**_ page of WE are FPV.
[![DroneBuilds](./images/DroneBuilds-WaF.png)](https://forum.wearefpv.fr/71-dronebuilds/ "DroneBuilds - Click to Access!")

The assembly of the frame is straightforward; however, a few clarifications:

* On one of the two sides of the **middle plate**, there are countersunk holes to accommodate countersunk screws. This side corresponds to the **underside**. Do not forget to install the stack screws before installing the middle plate.
* The pressnuts will be positioned on the underside of the bottom plate.
* An RX T antenna can be fixed to the rear of the JeNo using zip ties.
* Six screws of the top plate are countersunk screws to avoid damaging the battery.

## Inspiration
The JeNo 7" takes inspiration from the path laid out by the [KayouLoin](https://kayou-frames.com/fr/frames/25-kayouloin-7-frame.html).

While implementing 8mm arms remains quite evident, the KayouLoin innovates by introducing a **body that matches the quad's proportions**.

Certainly, this adds weight, but it provides the frame with unparalleled comfort in accommodating suitable batteries and absolute rigidity. If the cutting and sourcing of hardware are too constraining for you, we advise you to go directly to [Kayou's website](https://kayou-frames.com/fr/) !

## Tuning, Betaflight Preset ?
We probably won't provide a preset because motor setups have a huge influence, but here are some recommendations from Mark Spartz for 7" setups:

* ESCs PWM Frequency at **24KHz**
* **Reduce I** compared to a 5" (start with the slider at 0.5)

## Blackbox

Here is an overview of vibration distribution on the 3 axes for the JeNo 7". On the right with 6 mm arms (+ reinforcements), on the left with 8 mm arms. This is indeed the **unfiltered** gyro signal for a 3 minutes freestyle flight :

![JeNo 7 Blackbox](./images/JeNo7_BlackBox.jpg)

## Videos
Freestyle with JeNo :

[![JeNo 7" Maiden](./images/JeNo7_video_cruising.jpg)](https://www.youtube.com/watch?v=4mE-WnIyyHg "JeNo 7 Maiden - Click to Watch!")

## Builds examples
You can find build examples on [WE are FPV's DroneBuilds](https://forum.wearefpv.fr/71-dronebuilds/) :

* fr : [JeNo 7" Fork](https://forum.wearefpv.fr/topic/22645-jeno-7-fork)

## Authors

The JeNo was designed by :

* nochamo - [Youtube](https://www.youtube.com/user/nochamo)

## TPU
For now, a [minimalist TPU kit](https://github.com/WE-are-FPV/JeNo-7/tree/main/tpu) is available to you, containing:

* O3 antenna mount
* Double SMA Antenna Support
* 50V capacitor mount + spike absorber
* Rear bumper + RX antenna mount
* Front RX Support
* Arm protection with skids (6 and 8mm)

This offering **will expand** over time thanks to the community.

## Community (remixes and TPU)

**Fork/remix**

* [JeNo 7" Freestyle (Bash Edition)](https://www.printables.com/model/1073983-jeno-7freestyle-bash-edition), a mix between the JeNo 7" and the [JeNo PlatyStyle](https://www.printables.com/model/744619-jeno-51-platystyle-edition), otpimised for freestyle, by [Bash FPV](https://www.youtube.com/watch?v=s_6Gz9fyeIc&ab_channel=BashFPV)
* [JeNo 7" BBL - Freestyle Bando - RanxFPV Edition](JeNo 7" BBL - Freestyle Bando - RanxFPV Edition), a mix between the JeNo 7" and the remix from Bash FPV, for freestyle and bando (O3 and O4 Pro compatible), by [RankFPV](https://www.youtube.com/@RanxFPV)

**TPU**

In addition to the TPU options available on this page, you will find here some TPU designs created by the community.

* [Full TPU set](https://www.printables.com/fr/model/911148-jeno-7-tpu-kit-complet), [immortal-T antenna support](https://www.printables.com/fr/model/914154-jeno7-antenne-immortal-t) and a [DJI Action 2 mount](https://www.printables.com/fr/model/918051-jeno-7-dji-action-2-mount-25deg-filtre-nd-tbs) designed by [Jean-Lil](https://www.printables.com/fr/@JeanLil_707453)
* [Full TPU set, compatible with COB LEDs](https://makerworld.com/en/models/551901) by [BinaryWhite](https://www.youtube.com/@focal3drone803) (many TPUs are available, including RX and GPS mounts)
* [DJI Action 2 mount](https://www.printables.com/fr/model/960035-jeno-7-dji-action-2-mount-40deg-filtre-nd-tbs-batm) with a 40-degrees-tilt by [Lëtz Kwad](https://www.printables.com/fr/@LetzKwad_707453)

## Changelog

> [!TIP]
> Compatibility is consistently maintained between each version: if your frame was a v1, the parts from v1.2 will be compatible. The same applies to TPU accessories. That's why we don't keep the history of previous versions.

* 18/02/2025 :
  * Addition of TPU for softmounted camera plates (compatible with O4 Pro and O3)
* Version **1.1.1** (02/02/2025) :
  * Addition of cinematic and softmounted camera plates at 25° (for O4 Pro and O3)
* Version **1.1.0** (01/02/2025) :
  * Support for the Air Unit O4 Pro (camera plates)
* 21/05/2024 :
  * Addition of a top plate with XT60 cutout in the "extra" folder
* 04/06/2024 : 
  * Addition of 8" arms (untested) in the "extra" folder
* Version **1.0.0** (23/04/2024)