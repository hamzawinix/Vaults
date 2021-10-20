---

excalidraw-plugin: parsed

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
r1
 ^opo4CJC3

+ ^wNRqwY78

- ^yrnj8IPl

v0 ^TqIfKWmT

R2 ^PAvQRZNB

A = inf ^QSOffjLS

V0 = -R2/R1 * Vi
 ^YlaPQukz

r1
 ^rGodc1UH

+ ^kJjYw6Wd

- ^ewrbGPon

v0 ^9GPzBDK0

R2 ^pwlE3rzo

A = inf ^1U8D4xdd

V0 = (1+R2/R1)Vi ^rcJiDhE6

inverting scaling ^JZgujHM2

y = ax ^31bxBjTW

r1
 ^LvLMdIWi

+ ^3SDoOBRk

- ^iDrGjIxX

v0 ^nZfqGJ9G

R2 ^C1ncgitJ

A = inf ^ZbIutL0J

inverting amplifier with network feedback ^PBvYVJ5l

Ry ^KLEyVtb8

R3 ^oW18y4mO

i = o ^HccO0hNv

i = o ^ex9XOJ3P

delta V = 0 ^bCSSnE45

nodal @ 0
(0- Vi )/R1 + (0-V )/R2 + 0 = 0
-Vi/R1 = V/R2 ==> V = -R2/R1 * Vi ^AeWSCc4o

nodal @ V
v-0/R2 + V-0/R2 + V-V0 / Ry = 0
V0/Ry = V (1/R2 + 1/R3 + 1/Ry) ^pcaN4g72

it aint Ry its R4 ^WSQy1EyL

V0/Ry = -R2/R1 Vi (1/R2 + 1/R3 + 1/Ry)

 ^F9A8jTcy

question
R1 = 1k ohm
Ry = 100k
R2 = R3 = 10K
find gain:

-10(1+100/10 + 100/10)
-10(1+10+10)
-210 ^uD9OuxSN

V0 = -R2/R1 (1+Ry/R3 + Ry/R2)Vi  ^DPtYsHmw

Classifying gain ^ffitzty7

Rs (r series) ^1QbDMXhN

Voltage source ^zIXOnvlr

Rp ^pzHwW8zy

Current source ^thKgraCI

Voltage gain

Av = V0 / Vi (V/V)


Current gain

Ai = I0/Ii(A/A) ^L3Li0O0y

Gain impedence
Aim = V0/Ii (V/A) ^0y5pnXdI

Amplifier ^JC9mH6Oe

Amplifier ^2BzZBiu7

Amplifier ^DrxRqYDX

Conductunce Amplifier

Acn = i0/Vi (A/V) ^ITCwj8st

4 types of gain ^9Xh0TTmN

Rp ^OICKIKZc

Current source ^CpQxvoKv

r1
 ^y5XdnODg

+ ^wkNNWeKf

- ^X0LeGjCS

v0 ^VKzPczQP

A = inf ^FrCFzTEX

R3 ^dwCZ367Q

i = o ^RB0BfGuM

i = o ^NPdLrelz

delta V = 0 ^StITv9h2

+ ^Na7t5ieL

- ^NCqUJGAH

v0 ^TkTEChHt

R3 ^0ofMQC33

i = o ^6cFbl7P2

Rp  voltage accross it is zero so byebye
 ^Tf9rfx6v

Current source ^7gBuMiM4

Rl (r load) ^sPBpD4G2

R2 ^XYuFKL85

I0 ^oDhQf5A6

I2 ^h8m97BRR

Is ^ENCbwCQi

I0 = Is(1+R2/R3) ^pSAFUA6q

Gain on current ^FCrx52qD

Current source with a opamp ^wfPgmAsc

Summing amplifier ^FOi9uu4M

How to build  ^UuUiWQr4

+ ^8IOS2On8

V1 ^qNzDysNS

V2 ^TRKma8lS

V3 ^8ejA2OK2

R1 ^P4gHyMQZ

R2 ^T7XoRjJl

R3 ^TBEaKdaD

i =0 ^yrkc3NT8

V = 0 ^ArqbpmHe

V = 0 ^qmlq7Syb

Rf ^ZHwigR2g

0-V1 /R1 + 0-V2/R2 + 0-V3/R3 +0-V0/Rf +0 = 0

 ^hN0GAOpS

V0/Rf = -V1/R1 - V2/R2 - V3/R3 ^SmtfGDmQ

V0 = -Rf*V1/R1 - Rf*V2/R2 + Rf*V3/R3 ^93JvMQL4

but Rf = R1 + R2 + R3
 ^24qZRyeZ

V0 = -(V1 + V2 + V3) ^A8J1Sx8H

here Rf/R* = 1
so gain is one
but we summed stuff ^rxTBzSbZ

Non inverting Summing amplifier ^RHuj33pg

How to build  ^Wo1auutn

+ ^vijj6Jr5

V1 ^EMEIy39O

V2 ^8ImNs7s3

V3 ^QOjv5tJs

R1 ^MYAtsSLh

R2 ^LP3TLGME

R3 ^4LSo8Gpj

i =0 ^pg2KHxE8

V = 0 ^S8JSbz8o

V = 0 ^Mxi9IVXL

Rf ^A0IMgOfE

R5 ^lnVEVndF

R4 ^2CY1i2XD

V - V1 / R1 + V-V2/R2 + V-V3/R3 + V-0/R4 = 0

V-0 / R5 + V-V0/Rf + 0 = 0 ==> V(1/Rf +1/Rf) = V0/Rf

but V0 = (1+Rf/R5)V

V(1/R1 + 1/R2 + 1/R3 + 1/R4)

= V1/R1 + V2/R2 + V3 / R3 ^sK1LWuRl

##DO

assume R4 = inf
so 1/R4 = 0

V(1/R1 + 1/R2 + 1/R3) = V1/R1 + V2/R2 + V3/R3 ^cpJcRV82

##Continue ^0pwz28yw

Home work
 ^uImnxNKg

##DO

assume R4 = inf
so 1/R4 = 0

V(1/R1 + 1/R2 + 1/R3) = V1/R1 + V2/R2 + V3/R3 ^6sVPlwEG

+ ^Aa4Cro9W

9 problems of power ^29s5meZi

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://excalidraw.com",
	"elements": [
		{
			"type": "freedraw",
			"version": 97,
			"versionNonce": 754695502,
			"isDeleted": false,
			"id": "dUWzfGyVWeOGSz8lhL43r",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -66,
			"y": -252.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226,
			"height": 189,
			"seed": 1031538702,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1
				],
				[
					1,
					5
				],
				[
					20,
					19
				],
				[
					62,
					44
				],
				[
					114,
					76
				],
				[
					160,
					110
				],
				[
					208,
					139
				],
				[
					215,
					143
				],
				[
					211,
					144
				],
				[
					186,
					148
				],
				[
					145,
					162
				],
				[
					95,
					168
				],
				[
					51,
					174
				],
				[
					30,
					177
				],
				[
					26,
					178
				],
				[
					26,
					179
				],
				[
					26,
					181
				],
				[
					21,
					185
				],
				[
					16,
					187
				],
				[
					13,
					188
				],
				[
					12,
					189
				],
				[
					11,
					187
				],
				[
					11,
					184
				],
				[
					11,
					179
				],
				[
					10,
					153
				],
				[
					10,
					127
				],
				[
					10,
					102
				],
				[
					5,
					83
				],
				[
					1,
					67
				],
				[
					0,
					61
				],
				[
					-3,
					52
				],
				[
					-6,
					42
				],
				[
					-9,
					30
				],
				[
					-10,
					24
				],
				[
					-11,
					19
				],
				[
					-11,
					18
				],
				[
					-11,
					16
				],
				[
					-11,
					14
				],
				[
					-11,
					10
				],
				[
					-11,
					5
				],
				[
					-11,
					2
				],
				[
					-11,
					0
				],
				[
					-11,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 62,
			"versionNonce": 2141456018,
			"isDeleted": false,
			"id": "vq9IMewqjhWQUhayFhij9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -87,
			"y": -198.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206,
			"height": 5,
			"seed": 633202638,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-45,
					0
				],
				[
					-105,
					-2
				],
				[
					-163,
					-2
				],
				[
					-200,
					-2
				],
				[
					-205,
					-4
				],
				[
					-205,
					-4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 62,
			"versionNonce": 1098048398,
			"isDeleted": false,
			"id": "a0bHU43VU7V5-DAcJmlNx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -286,
			"y": -210.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 18,
			"seed": 1675163858,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					2
				],
				[
					0,
					4
				],
				[
					-2,
					13
				],
				[
					-4,
					17
				],
				[
					-5,
					18
				],
				[
					-9,
					13
				],
				[
					-14,
					6
				],
				[
					-18,
					2
				],
				[
					-18,
					2
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 91,
			"versionNonce": 1850303570,
			"isDeleted": false,
			"id": "8mGSn-cL0Lv1fQiYuB-2a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -305,
			"y": -210.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 147,
			"height": 16,
			"seed": 392434898,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					1
				],
				[
					-2,
					4
				],
				[
					-2,
					8
				],
				[
					-3,
					10
				],
				[
					-4,
					14
				],
				[
					-4,
					15
				],
				[
					-5,
					16
				],
				[
					-5,
					14
				],
				[
					-6,
					13
				],
				[
					-8,
					8
				],
				[
					-9,
					6
				],
				[
					-10,
					4
				],
				[
					-10,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				],
				[
					-11,
					7
				],
				[
					-12,
					10
				],
				[
					-13,
					12
				],
				[
					-14,
					13
				],
				[
					-16,
					12
				],
				[
					-17,
					11
				],
				[
					-19,
					8
				],
				[
					-21,
					5
				],
				[
					-22,
					3
				],
				[
					-24,
					3
				],
				[
					-26,
					4
				],
				[
					-27,
					5
				],
				[
					-28,
					5
				],
				[
					-31,
					5
				],
				[
					-33,
					6
				],
				[
					-44,
					7
				],
				[
					-54,
					9
				],
				[
					-68,
					9
				],
				[
					-99,
					9
				],
				[
					-124,
					9
				],
				[
					-139,
					9
				],
				[
					-145,
					9
				],
				[
					-146,
					9
				],
				[
					-146,
					9
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 11223502,
			"isDeleted": false,
			"id": "opo4CJC3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -314,
			"y": -247.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 50,
			"seed": 1081965774,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r1\n",
			"rawText": "r1\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 86,
			"versionNonce": 603785746,
			"isDeleted": false,
			"id": "UCgxVBPC4FYDo2Q112bQe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -59,
			"y": -107.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 189,
			"height": 126,
			"seed": 1718910610,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8,
					1
				],
				[
					-21,
					1
				],
				[
					-65,
					5
				],
				[
					-107,
					11
				],
				[
					-142,
					14
				],
				[
					-174,
					14
				],
				[
					-184,
					14
				],
				[
					-186,
					14
				],
				[
					-187,
					14
				],
				[
					-188,
					15
				],
				[
					-188,
					29
				],
				[
					-184,
					42
				],
				[
					-182,
					56
				],
				[
					-181,
					67
				],
				[
					-181,
					77
				],
				[
					-181,
					84
				],
				[
					-181,
					93
				],
				[
					-181,
					99
				],
				[
					-181,
					104
				],
				[
					-180,
					107
				],
				[
					-180,
					108
				],
				[
					-180,
					108
				],
				[
					-180,
					109
				],
				[
					-180,
					110
				],
				[
					-180,
					112
				],
				[
					-180,
					114
				],
				[
					-180,
					116
				],
				[
					-180,
					118
				],
				[
					-180,
					122
				],
				[
					-180,
					123
				],
				[
					-180,
					124
				],
				[
					-181,
					126
				],
				[
					-182,
					126
				],
				[
					-182,
					126
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 60,
			"versionNonce": 1841158158,
			"isDeleted": false,
			"id": "7IDi3_UhyM6uydPUT2FAD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220,
			"y": 15.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 7,
			"seed": 1295411406,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1
				],
				[
					-2,
					-2
				],
				[
					-13,
					-2
				],
				[
					-27,
					-2
				],
				[
					-45,
					2
				],
				[
					-56,
					5
				],
				[
					-60,
					5
				],
				[
					-61,
					5
				],
				[
					-61,
					5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 55,
			"versionNonce": 934672338,
			"isDeleted": false,
			"id": "cbJS_Cg860h5uCuJd49Sj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -241,
			"y": 34.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 4,
			"seed": 444311506,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					0
				],
				[
					-8,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 58,
			"versionNonce": 1084466766,
			"isDeleted": false,
			"id": "8rKf4ma_GvMY-tDcj6z0V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -228,
			"y": 55.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 1,
			"seed": 535437586,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-1,
					0
				],
				[
					-3,
					0
				],
				[
					-7,
					0
				],
				[
					-8,
					0
				],
				[
					-9,
					1
				],
				[
					-9,
					1
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 70,
			"versionNonce": 1233857938,
			"isDeleted": false,
			"id": "wNRqwY78",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -40,
			"y": -113.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 25,
			"seed": 1247496270,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 1245031566,
			"isDeleted": false,
			"id": "yrnj8IPl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -46,
			"y": -207.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 25,
			"seed": 321087886,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 53,
			"versionNonce": 1588833106,
			"isDeleted": false,
			"id": "ynVxCkjfLj89iWifh_Kl4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 140,
			"y": -114.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 675959250,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 75,
			"versionNonce": 1479338702,
			"isDeleted": false,
			"id": "AbbrrQWcZLWxq4oA1SarL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 137,
			"y": -115.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 105,
			"height": 1,
			"seed": 628720978,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					4,
					0
				],
				[
					13,
					0
				],
				[
					37,
					0
				],
				[
					55,
					0
				],
				[
					62,
					0
				],
				[
					63,
					0
				],
				[
					64,
					0
				],
				[
					64,
					0
				],
				[
					66,
					0
				],
				[
					70,
					0
				],
				[
					71,
					0
				],
				[
					72,
					0
				],
				[
					73,
					0
				],
				[
					75,
					0
				],
				[
					78,
					0
				],
				[
					83,
					0
				],
				[
					89,
					0
				],
				[
					93,
					0
				],
				[
					98,
					0
				],
				[
					100,
					0
				],
				[
					103,
					0
				],
				[
					104,
					0
				],
				[
					105,
					0
				],
				[
					105,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 1032220946,
			"isDeleted": false,
			"id": "TqIfKWmT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 190,
			"y": -152.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 25,
			"seed": 562261458,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "v0",
			"rawText": "v0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 144,
			"versionNonce": 421683470,
			"isDeleted": false,
			"id": "lKDiWhI8ZyeGCsKl7i0Bj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -159,
			"y": -199.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 324,
			"height": 211.99999999999997,
			"seed": 1508332750,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					-0.018404907975460436,
					-5.315315315315338
				],
				[
					0.9754601226993862,
					-4.360360360360383,
					0.5
				],
				[
					-0.018404907975460436,
					-6.270270270270293
				],
				[
					-1.0122699386503071,
					-13.909909909909931
				],
				[
					-1.0122699386503071,
					-27.2792792792793
				],
				[
					-1.0122699386503071,
					-41.60360360360362
				],
				[
					-1.0122699386503071,
					-55.92792792792794
				],
				[
					-1.0122699386503071,
					-67.3873873873874
				],
				[
					-1.0122699386503071,
					-79.80180180180182
				],
				[
					-1.0122699386503071,
					-89.35135135135137
				],
				[
					-1.0122699386503071,
					-99.85585585585586
				],
				[
					-3,
					-105.58558558558559
				],
				[
					-3,
					-108.45045045045046
				],
				[
					-3,
					-109.4054054054054
				],
				[
					-3,
					-112.27027027027027
				],
				[
					-3,
					-115.13513513513513
				],
				[
					-3,
					-116.0900900900901
				],
				[
					-3,
					-117.04504504504504
				],
				[
					7.932515337423313,
					-118
				],
				[
					30.791411042944787,
					-114.18018018018019
				],
				[
					84.4601226993865,
					-110.36036036036037
				],
				[
					134.15337423312883,
					-110.36036036036037
				],
				[
					177.88343558282207,
					-110.36036036036037
				],
				[
					209.68711656441715,
					-110.36036036036037
				],
				[
					223.601226993865,
					-110.36036036036037
				],
				[
					230.55828220858893,
					-110.36036036036037
				],
				[
					243.47852760736194,
					-110.36036036036037
				],
				[
					254.41104294478527,
					-110.36036036036037
				],
				[
					261.3680981595092,
					-110.36036036036037
				],
				[
					270.3128834355828,
					-110.36036036036037
				],
				[
					275.2822085889571,
					-110.36036036036037
				],
				[
					279.25766871165644,
					-110.36036036036037
				],
				[
					280.25153374233133,
					-109.4054054054054
				],
				[
					281.2453987730061,
					-109.4054054054054
				],
				[
					285.22085889570553,
					-109.4054054054054
				],
				[
					289.19631901840495,
					-109.4054054054054
				],
				[
					293.1717791411043,
					-109.4054054054054
				],
				[
					299.13496932515335,
					-109.4054054054054
				],
				[
					300.12883435582825,
					-109.4054054054054
				],
				[
					301.1226993865031,
					-108.45045045045046
				],
				[
					301.1226993865031,
					-108.45045045045046
				],
				[
					301.1226993865031,
					-105.58558558558559
				],
				[
					301.1226993865031,
					-100.81081081081082
				],
				[
					301.1226993865031,
					-91.26126126126127
				],
				[
					301.1226993865031,
					-75.981981981982
				],
				[
					301.1226993865031,
					-60.70270270270272
				],
				[
					302.1165644171779,
					-54.97297297297298
				],
				[
					304.1042944785276,
					-48.2882882882883
				],
				[
					305.09815950920245,
					-41.60360360360362
				],
				[
					305.09815950920245,
					-35.87387387387389
				],
				[
					305.09815950920245,
					-26.324324324324344
				],
				[
					307.0858895705522,
					-21.549549549549567
				],
				[
					308.07975460122697,
					-18.684684684684704
				],
				[
					309.07361963190186,
					-14.864864864864884
				],
				[
					311.06134969325154,
					-11.045045045045065
				],
				[
					312.0552147239264,
					-6.270270270270293
				],
				[
					312.0552147239264,
					0.41441441441439064
				],
				[
					312.0552147239264,
					16.648648648648624
				],
				[
					312.0552147239264,
					25.243243243243217
				],
				[
					314.0429447852761,
					30.972972972972943
				],
				[
					314.0429447852761,
					35.747747747747724
				],
				[
					315.0368098159509,
					44.342342342342306
				],
				[
					316.0306748466258,
					51.02702702702699
				],
				[
					320.00613496932516,
					72.036036036036
				],
				[
					320.00613496932516,
					84.45045045045042
				],
				[
					321,
					90.18018018018014
				],
				[
					321,
					93.045045045045
				],
				[
					321,
					93.99999999999996
				],
				[
					321,
					93.99999999999996
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 105,
			"versionNonce": 1232764626,
			"isDeleted": false,
			"id": "MUiXhtXeMuPz965vUrHjJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -23,
			"y": -310.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 79,
			"height": 28,
			"seed": 1235684238,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1,
					-1
				],
				[
					2,
					-1
				],
				[
					3,
					-2
				],
				[
					3,
					-2
				],
				[
					4,
					-2
				],
				[
					5,
					-2
				],
				[
					6,
					-3
				],
				[
					9,
					-6
				],
				[
					13,
					-10
				],
				[
					17,
					-14
				],
				[
					18,
					-16
				],
				[
					18,
					-15
				],
				[
					19,
					-8
				],
				[
					20,
					-4
				],
				[
					21,
					0
				],
				[
					22,
					4
				],
				[
					23,
					7
				],
				[
					23,
					10
				],
				[
					24,
					10
				],
				[
					27,
					7
				],
				[
					28,
					4
				],
				[
					30,
					-1
				],
				[
					32,
					-6
				],
				[
					33,
					-8
				],
				[
					33,
					-8
				],
				[
					33,
					-3
				],
				[
					34,
					1
				],
				[
					34,
					2
				],
				[
					35,
					3
				],
				[
					36,
					3
				],
				[
					39,
					0
				],
				[
					46,
					-8
				],
				[
					49,
					-10
				],
				[
					51,
					-12
				],
				[
					52,
					-12
				],
				[
					52,
					-7
				],
				[
					53,
					-4
				],
				[
					54,
					-2
				],
				[
					55,
					1
				],
				[
					56,
					2
				],
				[
					58,
					0
				],
				[
					60,
					-1
				],
				[
					64,
					-6
				],
				[
					68,
					-13
				],
				[
					71,
					-16
				],
				[
					71,
					-18
				],
				[
					72,
					-15
				],
				[
					73,
					-12
				],
				[
					75,
					-7
				],
				[
					76,
					-3
				],
				[
					77,
					-2
				],
				[
					78,
					-1
				],
				[
					79,
					0
				],
				[
					79,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 9375566,
			"isDeleted": false,
			"id": "PAvQRZNB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 8,
			"y": -374.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 25,
			"seed": 549685454,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R2",
			"rawText": "R2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 58,
			"versionNonce": 1596380306,
			"isDeleted": false,
			"id": "QSOffjLS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2,
			"y": -159.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 25,
			"seed": 1489274834,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A = inf",
			"rawText": "A = inf",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 718009742,
			"isDeleted": false,
			"id": "YlaPQukz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -70.7626262626263,
			"y": 4.3459595959595845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 166,
			"height": 50,
			"seed": 1499497422,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0 = -R2/R1 * Vi\n",
			"rawText": "V0 = -R2/R1 * Vi\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 147,
			"versionNonce": 809661010,
			"isDeleted": false,
			"id": "sUz98SYHjcvCHx4UGOBVy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 745.0909090909091,
			"y": -251.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226,
			"height": 189,
			"seed": 1423311438,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1
				],
				[
					1,
					5
				],
				[
					20,
					19
				],
				[
					62,
					44
				],
				[
					114,
					76
				],
				[
					160,
					110
				],
				[
					208,
					139
				],
				[
					215,
					143
				],
				[
					211,
					144
				],
				[
					186,
					148
				],
				[
					145,
					162
				],
				[
					95,
					168
				],
				[
					51,
					174
				],
				[
					30,
					177
				],
				[
					26,
					178
				],
				[
					26,
					179
				],
				[
					26,
					181
				],
				[
					21,
					185
				],
				[
					16,
					187
				],
				[
					13,
					188
				],
				[
					12,
					189
				],
				[
					11,
					187
				],
				[
					11,
					184
				],
				[
					11,
					179
				],
				[
					10,
					153
				],
				[
					10,
					127
				],
				[
					10,
					102
				],
				[
					5,
					83
				],
				[
					1,
					67
				],
				[
					0,
					61
				],
				[
					-3,
					52
				],
				[
					-6,
					42
				],
				[
					-9,
					30
				],
				[
					-10,
					24
				],
				[
					-11,
					19
				],
				[
					-11,
					18
				],
				[
					-11,
					16
				],
				[
					-11,
					14
				],
				[
					-11,
					10
				],
				[
					-11,
					5
				],
				[
					-11,
					2
				],
				[
					-11,
					0
				],
				[
					-11,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 112,
			"versionNonce": 1091703758,
			"isDeleted": false,
			"id": "YlCJ-EZ9W0wt3ji6rr2c8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 724.0909090909091,
			"y": -197.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206,
			"height": 5,
			"seed": 222073234,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-45,
					0
				],
				[
					-105,
					-2
				],
				[
					-163,
					-2
				],
				[
					-200,
					-2
				],
				[
					-205,
					-4
				],
				[
					-205,
					-4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 112,
			"versionNonce": 530864146,
			"isDeleted": false,
			"id": "RdgdxwiWlOlgkoVlDn0Fy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 525.0909090909091,
			"y": -209.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 18,
			"seed": 1606191246,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					2
				],
				[
					0,
					4
				],
				[
					-2,
					13
				],
				[
					-4,
					17
				],
				[
					-5,
					18
				],
				[
					-9,
					13
				],
				[
					-14,
					6
				],
				[
					-18,
					2
				],
				[
					-18,
					2
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 141,
			"versionNonce": 1568303630,
			"isDeleted": false,
			"id": "vlWFkinLgO6w_tseSZ75E",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 506.0909090909091,
			"y": -209.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 147,
			"height": 16,
			"seed": 1855491922,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					1
				],
				[
					-2,
					4
				],
				[
					-2,
					8
				],
				[
					-3,
					10
				],
				[
					-4,
					14
				],
				[
					-4,
					15
				],
				[
					-5,
					16
				],
				[
					-5,
					14
				],
				[
					-6,
					13
				],
				[
					-8,
					8
				],
				[
					-9,
					6
				],
				[
					-10,
					4
				],
				[
					-10,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				],
				[
					-11,
					7
				],
				[
					-12,
					10
				],
				[
					-13,
					12
				],
				[
					-14,
					13
				],
				[
					-16,
					12
				],
				[
					-17,
					11
				],
				[
					-19,
					8
				],
				[
					-21,
					5
				],
				[
					-22,
					3
				],
				[
					-24,
					3
				],
				[
					-26,
					4
				],
				[
					-27,
					5
				],
				[
					-28,
					5
				],
				[
					-31,
					5
				],
				[
					-33,
					6
				],
				[
					-44,
					7
				],
				[
					-54,
					9
				],
				[
					-68,
					9
				],
				[
					-99,
					9
				],
				[
					-124,
					9
				],
				[
					-139,
					9
				],
				[
					-145,
					9
				],
				[
					-146,
					9
				],
				[
					-146,
					9
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 87,
			"versionNonce": 490964434,
			"isDeleted": false,
			"id": "rGodc1UH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 497.0909090909091,
			"y": -246.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 50,
			"seed": 1350059726,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r1\n",
			"rawText": "r1\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 136,
			"versionNonce": 1862137934,
			"isDeleted": false,
			"id": "RiRf8RCfCtFyLD60Hm9JY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 752.0909090909091,
			"y": -106.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 189,
			"height": 126,
			"seed": 1194251538,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8,
					1
				],
				[
					-21,
					1
				],
				[
					-65,
					5
				],
				[
					-107,
					11
				],
				[
					-142,
					14
				],
				[
					-174,
					14
				],
				[
					-184,
					14
				],
				[
					-186,
					14
				],
				[
					-187,
					14
				],
				[
					-188,
					15
				],
				[
					-188,
					29
				],
				[
					-184,
					42
				],
				[
					-182,
					56
				],
				[
					-181,
					67
				],
				[
					-181,
					77
				],
				[
					-181,
					84
				],
				[
					-181,
					93
				],
				[
					-181,
					99
				],
				[
					-181,
					104
				],
				[
					-180,
					107
				],
				[
					-180,
					108
				],
				[
					-180,
					108
				],
				[
					-180,
					109
				],
				[
					-180,
					110
				],
				[
					-180,
					112
				],
				[
					-180,
					114
				],
				[
					-180,
					116
				],
				[
					-180,
					118
				],
				[
					-180,
					122
				],
				[
					-180,
					123
				],
				[
					-180,
					124
				],
				[
					-181,
					126
				],
				[
					-182,
					126
				],
				[
					-182,
					126
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 133,
			"versionNonce": 37157778,
			"isDeleted": false,
			"id": "uVkduC_oZRYplB6JoLVAV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 378.86868686868684,
			"y": -149.1237373737374,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 7,
			"seed": 664943886,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1
				],
				[
					-2,
					-2
				],
				[
					-13,
					-2
				],
				[
					-27,
					-2
				],
				[
					-45,
					2
				],
				[
					-56,
					5
				],
				[
					-60,
					5
				],
				[
					-61,
					5
				],
				[
					-61,
					5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 128,
			"versionNonce": 494255758,
			"isDeleted": false,
			"id": "Y9tOal_nsUXBUrgF-4ok8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 357.86868686868684,
			"y": -130.1237373737374,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 4,
			"seed": 1215718098,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					0
				],
				[
					-8,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 131,
			"versionNonce": 1823848786,
			"isDeleted": false,
			"id": "yK_syoNBnZbWbDlAE89r2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 370.86868686868684,
			"y": -109.12373737373741,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 1,
			"seed": 1790143310,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-1,
					0
				],
				[
					-3,
					0
				],
				[
					-7,
					0
				],
				[
					-8,
					0
				],
				[
					-9,
					1
				],
				[
					-9,
					1
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 765115598,
			"isDeleted": false,
			"id": "kJjYw6Wd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 771.0909090909091,
			"y": -112.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 25,
			"seed": 1560688786,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 78,
			"versionNonce": 471252754,
			"isDeleted": false,
			"id": "ewrbGPon",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 765.0909090909091,
			"y": -206.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 25,
			"seed": 134533518,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 103,
			"versionNonce": 1694888718,
			"isDeleted": false,
			"id": "rVtLBm6V6tqXgJIDVmexI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 951.0909090909091,
			"y": -113.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 76895826,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 125,
			"versionNonce": 1288768722,
			"isDeleted": false,
			"id": "tVyUWMr9OxrOU8_i7UUZK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 948.0909090909091,
			"y": -114.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 105,
			"height": 1,
			"seed": 986673102,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					4,
					0
				],
				[
					13,
					0
				],
				[
					37,
					0
				],
				[
					55,
					0
				],
				[
					62,
					0
				],
				[
					63,
					0
				],
				[
					64,
					0
				],
				[
					64,
					0
				],
				[
					66,
					0
				],
				[
					70,
					0
				],
				[
					71,
					0
				],
				[
					72,
					0
				],
				[
					73,
					0
				],
				[
					75,
					0
				],
				[
					78,
					0
				],
				[
					83,
					0
				],
				[
					89,
					0
				],
				[
					93,
					0
				],
				[
					98,
					0
				],
				[
					100,
					0
				],
				[
					103,
					0
				],
				[
					104,
					0
				],
				[
					105,
					0
				],
				[
					105,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 1848664398,
			"isDeleted": false,
			"id": "9GPzBDK0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1001.0909090909091,
			"y": -151.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 25,
			"seed": 804961298,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "v0",
			"rawText": "v0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 343646866,
			"isDeleted": false,
			"id": "z7KTQIE3FNxeoE_M3mRWB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 652.0909090909091,
			"y": -198.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 324,
			"height": 211.99999999999997,
			"seed": 1865172494,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					-0.018404907975460436,
					-5.315315315315338
				],
				[
					0.9754601226993862,
					-4.360360360360383,
					0.5
				],
				[
					-0.018404907975460436,
					-6.270270270270293
				],
				[
					-1.0122699386503071,
					-13.909909909909931
				],
				[
					-1.0122699386503071,
					-27.2792792792793
				],
				[
					-1.0122699386503071,
					-41.60360360360362
				],
				[
					-1.0122699386503071,
					-55.92792792792794
				],
				[
					-1.0122699386503071,
					-67.3873873873874
				],
				[
					-1.0122699386503071,
					-79.80180180180182
				],
				[
					-1.0122699386503071,
					-89.35135135135137
				],
				[
					-1.0122699386503071,
					-99.85585585585586
				],
				[
					-3,
					-105.58558558558559
				],
				[
					-3,
					-108.45045045045046
				],
				[
					-3,
					-109.4054054054054
				],
				[
					-3,
					-112.27027027027027
				],
				[
					-3,
					-115.13513513513513
				],
				[
					-3,
					-116.0900900900901
				],
				[
					-3,
					-117.04504504504504
				],
				[
					7.932515337423313,
					-118
				],
				[
					30.791411042944787,
					-114.18018018018019
				],
				[
					84.4601226993865,
					-110.36036036036037
				],
				[
					134.15337423312883,
					-110.36036036036037
				],
				[
					177.88343558282207,
					-110.36036036036037
				],
				[
					209.68711656441715,
					-110.36036036036037
				],
				[
					223.601226993865,
					-110.36036036036037
				],
				[
					230.55828220858893,
					-110.36036036036037
				],
				[
					243.47852760736194,
					-110.36036036036037
				],
				[
					254.41104294478527,
					-110.36036036036037
				],
				[
					261.3680981595092,
					-110.36036036036037
				],
				[
					270.3128834355828,
					-110.36036036036037
				],
				[
					275.2822085889571,
					-110.36036036036037
				],
				[
					279.25766871165644,
					-110.36036036036037
				],
				[
					280.25153374233133,
					-109.4054054054054
				],
				[
					281.2453987730061,
					-109.4054054054054
				],
				[
					285.22085889570553,
					-109.4054054054054
				],
				[
					289.19631901840495,
					-109.4054054054054
				],
				[
					293.1717791411043,
					-109.4054054054054
				],
				[
					299.13496932515335,
					-109.4054054054054
				],
				[
					300.12883435582825,
					-109.4054054054054
				],
				[
					301.1226993865031,
					-108.45045045045046
				],
				[
					301.1226993865031,
					-108.45045045045046
				],
				[
					301.1226993865031,
					-105.58558558558559
				],
				[
					301.1226993865031,
					-100.81081081081082
				],
				[
					301.1226993865031,
					-91.26126126126127
				],
				[
					301.1226993865031,
					-75.981981981982
				],
				[
					301.1226993865031,
					-60.70270270270272
				],
				[
					302.1165644171779,
					-54.97297297297298
				],
				[
					304.1042944785276,
					-48.2882882882883
				],
				[
					305.09815950920245,
					-41.60360360360362
				],
				[
					305.09815950920245,
					-35.87387387387389
				],
				[
					305.09815950920245,
					-26.324324324324344
				],
				[
					307.0858895705522,
					-21.549549549549567
				],
				[
					308.07975460122697,
					-18.684684684684704
				],
				[
					309.07361963190186,
					-14.864864864864884
				],
				[
					311.06134969325154,
					-11.045045045045065
				],
				[
					312.0552147239264,
					-6.270270270270293
				],
				[
					312.0552147239264,
					0.41441441441439064
				],
				[
					312.0552147239264,
					16.648648648648624
				],
				[
					312.0552147239264,
					25.243243243243217
				],
				[
					314.0429447852761,
					30.972972972972943
				],
				[
					314.0429447852761,
					35.747747747747724
				],
				[
					315.0368098159509,
					44.342342342342306
				],
				[
					316.0306748466258,
					51.02702702702699
				],
				[
					320.00613496932516,
					72.036036036036
				],
				[
					320.00613496932516,
					84.45045045045042
				],
				[
					321,
					90.18018018018014
				],
				[
					321,
					93.045045045045
				],
				[
					321,
					93.99999999999996
				],
				[
					321,
					93.99999999999996
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 155,
			"versionNonce": 1014171534,
			"isDeleted": false,
			"id": "gg_4FCSlYQ9RkqJRZXp1t",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 788.0909090909091,
			"y": -309.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 79,
			"height": 28,
			"seed": 489515474,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1,
					-1
				],
				[
					2,
					-1
				],
				[
					3,
					-2
				],
				[
					3,
					-2
				],
				[
					4,
					-2
				],
				[
					5,
					-2
				],
				[
					6,
					-3
				],
				[
					9,
					-6
				],
				[
					13,
					-10
				],
				[
					17,
					-14
				],
				[
					18,
					-16
				],
				[
					18,
					-15
				],
				[
					19,
					-8
				],
				[
					20,
					-4
				],
				[
					21,
					0
				],
				[
					22,
					4
				],
				[
					23,
					7
				],
				[
					23,
					10
				],
				[
					24,
					10
				],
				[
					27,
					7
				],
				[
					28,
					4
				],
				[
					30,
					-1
				],
				[
					32,
					-6
				],
				[
					33,
					-8
				],
				[
					33,
					-8
				],
				[
					33,
					-3
				],
				[
					34,
					1
				],
				[
					34,
					2
				],
				[
					35,
					3
				],
				[
					36,
					3
				],
				[
					39,
					0
				],
				[
					46,
					-8
				],
				[
					49,
					-10
				],
				[
					51,
					-12
				],
				[
					52,
					-12
				],
				[
					52,
					-7
				],
				[
					53,
					-4
				],
				[
					54,
					-2
				],
				[
					55,
					1
				],
				[
					56,
					2
				],
				[
					58,
					0
				],
				[
					60,
					-1
				],
				[
					64,
					-6
				],
				[
					68,
					-13
				],
				[
					71,
					-16
				],
				[
					71,
					-18
				],
				[
					72,
					-15
				],
				[
					73,
					-12
				],
				[
					75,
					-7
				],
				[
					76,
					-3
				],
				[
					77,
					-2
				],
				[
					78,
					-1
				],
				[
					79,
					0
				],
				[
					79,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 1036877906,
			"isDeleted": false,
			"id": "pwlE3rzo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 819.0909090909091,
			"y": -373.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 25,
			"seed": 638866510,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R2",
			"rawText": "R2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1879500238,
			"isDeleted": false,
			"id": "1U8D4xdd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 809.0909090909091,
			"y": -158.56818181818187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 25,
			"seed": 860118930,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A = inf",
			"rawText": "A = inf",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 69,
			"versionNonce": 614311442,
			"isDeleted": false,
			"id": "3R_cWkRsctT108ejoJpZE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 363.2676767676768,
			"y": -202.42297979798008,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.444444444444457,
			"height": 53.333333333333314,
			"seed": 344271054,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.1111111111110858,
					1.1111111111111427
				],
				[
					-3.3333333333333712,
					2.2222222222222285
				],
				[
					-4.444444444444457,
					4.444444444444457
				],
				[
					-8.888888888888914,
					14.444444444444457
				],
				[
					-14.444444444444457,
					24.4444444444444
				],
				[
					-17.77777777777783,
					33.333333333333314
				],
				[
					-22.222222222222285,
					38.88888888888886
				],
				[
					-23.33333333333337,
					42.22222222222217
				],
				[
					-24.444444444444457,
					44.4444444444444
				],
				[
					-24.444444444444457,
					46.66666666666663
				],
				[
					-24.444444444444457,
					47.77777777777777
				],
				[
					-24.444444444444457,
					48.88888888888886
				],
				[
					-23.33333333333337,
					51.11111111111103
				],
				[
					-21.111111111111086,
					52.22222222222223
				],
				[
					-20,
					52.22222222222223
				],
				[
					-18.888888888888914,
					53.333333333333314
				],
				[
					-17.77777777777783,
					53.333333333333314
				],
				[
					-17.77777777777783,
					53.333333333333314
				],
				[
					-17.77777777777783,
					53.333333333333314
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 973405198,
			"isDeleted": false,
			"id": "rcJiDhE6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 757.7121212121215,
			"y": 19.222222222222342,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 161,
			"height": 25,
			"seed": 467921810,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0 = (1+R2/R1)Vi",
			"rawText": "V0 = (1+R2/R1)Vi",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 69,
			"versionNonce": 300094418,
			"isDeleted": false,
			"id": "JZgujHM2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -70.06565656565715,
			"y": -444.1111111111109,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 152,
			"height": 25,
			"seed": 505660238,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "inverting scaling",
			"rawText": "inverting scaling",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 118,
			"versionNonce": 1080445518,
			"isDeleted": false,
			"id": "31bxBjTW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 243.26767676767656,
			"y": 147.00000000000014,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 219,
			"height": 83,
			"seed": 430021202,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 66.22222222222214,
			"fontFamily": 1,
			"text": "y = ax",
			"rawText": "y = ax",
			"baseline": 59,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "arrow",
			"version": 126,
			"versionNonce": 397724050,
			"isDeleted": false,
			"id": "Y4vPfWCrxHUDC3tes4aPK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 745.4898989898988,
			"y": 57.11111111111131,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 226.66666666666674,
			"height": 87.77777777777783,
			"seed": 1721360462,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-226.66666666666674,
					87.77777777777783
				]
			]
		},
		{
			"type": "arrow",
			"version": 154,
			"versionNonce": 33804430,
			"isDeleted": false,
			"id": "_7SWUTriow_YYVxjnCQTh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 76.60101010100988,
			"y": 21.555555555555827,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 150,
			"height": 125.55555555555549,
			"seed": 1449353234,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					150,
					125.55555555555549
				]
			]
		},
		{
			"type": "freedraw",
			"version": 119,
			"versionNonce": 1833551698,
			"isDeleted": false,
			"id": "OekD2LvlCflxBb2hVDoqX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 40.339105339104776,
			"y": 546.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226,
			"height": 189,
			"seed": 899740946,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1
				],
				[
					1,
					5
				],
				[
					20,
					19
				],
				[
					62,
					44
				],
				[
					114,
					76
				],
				[
					160,
					110
				],
				[
					208,
					139
				],
				[
					215,
					143
				],
				[
					211,
					144
				],
				[
					186,
					148
				],
				[
					145,
					162
				],
				[
					95,
					168
				],
				[
					51,
					174
				],
				[
					30,
					177
				],
				[
					26,
					178
				],
				[
					26,
					179
				],
				[
					26,
					181
				],
				[
					21,
					185
				],
				[
					16,
					187
				],
				[
					13,
					188
				],
				[
					12,
					189
				],
				[
					11,
					187
				],
				[
					11,
					184
				],
				[
					11,
					179
				],
				[
					10,
					153
				],
				[
					10,
					127
				],
				[
					10,
					102
				],
				[
					5,
					83
				],
				[
					1,
					67
				],
				[
					0,
					61
				],
				[
					-3,
					52
				],
				[
					-6,
					42
				],
				[
					-9,
					30
				],
				[
					-10,
					24
				],
				[
					-11,
					19
				],
				[
					-11,
					18
				],
				[
					-11,
					16
				],
				[
					-11,
					14
				],
				[
					-11,
					10
				],
				[
					-11,
					5
				],
				[
					-11,
					2
				],
				[
					-11,
					0
				],
				[
					-11,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 84,
			"versionNonce": 982945486,
			"isDeleted": false,
			"id": "A0_XoL2q8njx4OMcjoTR3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 19.339105339104776,
			"y": 600.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206,
			"height": 5,
			"seed": 685907214,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-45,
					0
				],
				[
					-105,
					-2
				],
				[
					-163,
					-2
				],
				[
					-200,
					-2
				],
				[
					-205,
					-4
				],
				[
					-205,
					-4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 84,
			"versionNonce": 1257835794,
			"isDeleted": false,
			"id": "Ku5Edl0KIsBB6sSVzx_L0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -179.66089466089522,
			"y": 588.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 18,
			"seed": 1671725778,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					2
				],
				[
					0,
					4
				],
				[
					-2,
					13
				],
				[
					-4,
					17
				],
				[
					-5,
					18
				],
				[
					-9,
					13
				],
				[
					-14,
					6
				],
				[
					-18,
					2
				],
				[
					-18,
					2
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 113,
			"versionNonce": 1186432270,
			"isDeleted": false,
			"id": "jcziAApYeMJovwfU_PI-Z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -198.66089466089522,
			"y": 588.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 147,
			"height": 16,
			"seed": 2029472590,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					1
				],
				[
					-2,
					4
				],
				[
					-2,
					8
				],
				[
					-3,
					10
				],
				[
					-4,
					14
				],
				[
					-4,
					15
				],
				[
					-5,
					16
				],
				[
					-5,
					14
				],
				[
					-6,
					13
				],
				[
					-8,
					8
				],
				[
					-9,
					6
				],
				[
					-10,
					4
				],
				[
					-10,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				],
				[
					-11,
					7
				],
				[
					-12,
					10
				],
				[
					-13,
					12
				],
				[
					-14,
					13
				],
				[
					-16,
					12
				],
				[
					-17,
					11
				],
				[
					-19,
					8
				],
				[
					-21,
					5
				],
				[
					-22,
					3
				],
				[
					-24,
					3
				],
				[
					-26,
					4
				],
				[
					-27,
					5
				],
				[
					-28,
					5
				],
				[
					-31,
					5
				],
				[
					-33,
					6
				],
				[
					-44,
					7
				],
				[
					-54,
					9
				],
				[
					-68,
					9
				],
				[
					-99,
					9
				],
				[
					-124,
					9
				],
				[
					-139,
					9
				],
				[
					-145,
					9
				],
				[
					-146,
					9
				],
				[
					-146,
					9
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 83,
			"versionNonce": 1178180306,
			"isDeleted": false,
			"id": "LvLMdIWi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -207.66089466089522,
			"y": 551.3531746031746,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 50,
			"seed": 762337426,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r1\n",
			"rawText": "r1\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 108,
			"versionNonce": 132100942,
			"isDeleted": false,
			"id": "iaOLGR7w3DOzf3nP7o4R8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 47.339105339104776,
			"y": 691.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 189,
			"height": 126,
			"seed": 1657581966,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8,
					1
				],
				[
					-21,
					1
				],
				[
					-65,
					5
				],
				[
					-107,
					11
				],
				[
					-142,
					14
				],
				[
					-174,
					14
				],
				[
					-184,
					14
				],
				[
					-186,
					14
				],
				[
					-187,
					14
				],
				[
					-188,
					15
				],
				[
					-188,
					29
				],
				[
					-184,
					42
				],
				[
					-182,
					56
				],
				[
					-181,
					67
				],
				[
					-181,
					77
				],
				[
					-181,
					84
				],
				[
					-181,
					93
				],
				[
					-181,
					99
				],
				[
					-181,
					104
				],
				[
					-180,
					107
				],
				[
					-180,
					108
				],
				[
					-180,
					108
				],
				[
					-180,
					109
				],
				[
					-180,
					110
				],
				[
					-180,
					112
				],
				[
					-180,
					114
				],
				[
					-180,
					116
				],
				[
					-180,
					118
				],
				[
					-180,
					122
				],
				[
					-180,
					123
				],
				[
					-180,
					124
				],
				[
					-181,
					126
				],
				[
					-182,
					126
				],
				[
					-182,
					126
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 82,
			"versionNonce": 765620370,
			"isDeleted": false,
			"id": "ONRuaW1Nabk3gqQdKzmz_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -113.66089466089522,
			"y": 814.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 7,
			"seed": 45839954,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1
				],
				[
					-2,
					-2
				],
				[
					-13,
					-2
				],
				[
					-27,
					-2
				],
				[
					-45,
					2
				],
				[
					-56,
					5
				],
				[
					-60,
					5
				],
				[
					-61,
					5
				],
				[
					-61,
					5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 77,
			"versionNonce": 1214781838,
			"isDeleted": false,
			"id": "JM9EZbSYQxtAbExecAWOu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -134.66089466089522,
			"y": 833.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 4,
			"seed": 832262094,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					0
				],
				[
					-8,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 80,
			"versionNonce": 1693093458,
			"isDeleted": false,
			"id": "ZC5qzOBn6mgJISziIVadE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -121.66089466089522,
			"y": 854.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 1,
			"seed": 1146936338,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-1,
					0
				],
				[
					-3,
					0
				],
				[
					-7,
					0
				],
				[
					-8,
					0
				],
				[
					-9,
					1
				],
				[
					-9,
					1
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 92,
			"versionNonce": 529119182,
			"isDeleted": false,
			"id": "3SDoOBRk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 66.33910533910478,
			"y": 685.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 25,
			"seed": 1635526158,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 74,
			"versionNonce": 1089008658,
			"isDeleted": false,
			"id": "iDrGjIxX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 60.339105339104776,
			"y": 591.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 25,
			"seed": 541821394,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 75,
			"versionNonce": 1432194574,
			"isDeleted": false,
			"id": "GdqGQLUiM5F09Og5b3J60",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 246.33910533910478,
			"y": 684.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 57160782,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 97,
			"versionNonce": 1670685138,
			"isDeleted": false,
			"id": "ubSAAAUj9G4qI8gKcUT1b",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 243.33910533910478,
			"y": 683.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 105,
			"height": 1,
			"seed": 1839103890,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					4,
					0
				],
				[
					13,
					0
				],
				[
					37,
					0
				],
				[
					55,
					0
				],
				[
					62,
					0
				],
				[
					63,
					0
				],
				[
					64,
					0
				],
				[
					64,
					0
				],
				[
					66,
					0
				],
				[
					70,
					0
				],
				[
					71,
					0
				],
				[
					72,
					0
				],
				[
					73,
					0
				],
				[
					75,
					0
				],
				[
					78,
					0
				],
				[
					83,
					0
				],
				[
					89,
					0
				],
				[
					93,
					0
				],
				[
					98,
					0
				],
				[
					100,
					0
				],
				[
					103,
					0
				],
				[
					104,
					0
				],
				[
					105,
					0
				],
				[
					105,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 1188863054,
			"isDeleted": false,
			"id": "nZfqGJ9G",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 296.3391053391048,
			"y": 646.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 25,
			"seed": 557349518,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "v0",
			"rawText": "v0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 108,
			"versionNonce": 402954130,
			"isDeleted": false,
			"id": "C1ncgitJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 54.33910533910455,
			"y": 407.21031746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 25,
			"seed": 778912530,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R2",
			"rawText": "R2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 1239409294,
			"isDeleted": false,
			"id": "ZbIutL0J",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 104.33910533910478,
			"y": 639.3531746031747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 25,
			"seed": 743026446,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A = inf",
			"rawText": "A = inf",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 779081042,
			"isDeleted": false,
			"id": "PBvYVJ5l",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -88.16089466089522,
			"y": 350.33333333333337,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 395,
			"height": 25,
			"seed": 1038953550,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "inverting amplifier with network feedback",
			"rawText": "inverting amplifier with network feedback",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "line",
			"version": 162,
			"versionNonce": 287334606,
			"isDeleted": false,
			"id": "QNwE6lz6JR0H6EEXBxibx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -78.16089466089517,
			"y": 597.9047619047619,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127.14285714285717,
			"height": 131.4285714285714,
			"seed": 2042036878,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
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
					-1.428571428571388,
					-125.71428571428567
				],
				[
					125.71428571428578,
					-131.4285714285714
				]
			]
		},
		{
			"type": "freedraw",
			"version": 171,
			"versionNonce": 1479367442,
			"isDeleted": false,
			"id": "HQlszNOUs7GLgKVISFkh6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 46.12481962481917,
			"y": 463.6190476190477,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 194.28571428571422,
			"height": 128.57142857142856,
			"seed": 2062533902,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					4.285714285714221,
					-2.8571428571428896
				],
				[
					8.571428571428555,
					-12.85714285714289
				],
				[
					10,
					-14.285714285714334
				],
				[
					11.428571428571445,
					-11.428571428571445
				],
				[
					11.428571428571445,
					-8.571428571428612
				],
				[
					14.28571428571422,
					0
				],
				[
					15.714285714285666,
					5.714285714285666
				],
				[
					17.14285714285711,
					10
				],
				[
					18.571428571428555,
					12.857142857142833
				],
				[
					18.571428571428555,
					14.285714285714278
				],
				[
					17.14285714285711,
					15.714285714285666
				],
				[
					15.714285714285666,
					4.285714285714278
				],
				[
					18.571428571428555,
					-7.142857142857167
				],
				[
					22.85714285714289,
					-15.714285714285722
				],
				[
					25.714285714285666,
					-20
				],
				[
					27.14285714285711,
					-18.571428571428612
				],
				[
					30,
					-11.428571428571445
				],
				[
					32.85714285714289,
					-5.714285714285722
				],
				[
					34.28571428571422,
					-2.8571428571428896
				],
				[
					34.28571428571422,
					-1.4285714285714448
				],
				[
					34.28571428571422,
					0
				],
				[
					35.714285714285666,
					-1.4285714285714448
				],
				[
					38.571428571428555,
					-5.714285714285722
				],
				[
					38.571428571428555,
					-8.571428571428612
				],
				[
					41.428571428571445,
					-15.714285714285722
				],
				[
					41.428571428571445,
					-18.571428571428612
				],
				[
					42.85714285714289,
					-20
				],
				[
					42.85714285714289,
					-17.142857142857167
				],
				[
					42.85714285714289,
					-12.85714285714289
				],
				[
					42.85714285714289,
					-8.571428571428612
				],
				[
					45.714285714285666,
					1.428571428571388
				],
				[
					45.714285714285666,
					4.285714285714278
				],
				[
					47.14285714285711,
					8.571428571428555
				],
				[
					48.571428571428555,
					11.428571428571388
				],
				[
					51.428571428571445,
					10
				],
				[
					52.85714285714289,
					8.571428571428555
				],
				[
					55.714285714285666,
					5.714285714285666
				],
				[
					57.14285714285711,
					5.714285714285666
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					58.571428571428555,
					2.857142857142833
				],
				[
					58.571428571428555,
					0
				],
				[
					58.571428571428555,
					-4.285714285714334
				],
				[
					58.571428571428555,
					-7.142857142857167
				],
				[
					58.571428571428555,
					-10
				],
				[
					60,
					-11.428571428571445
				],
				[
					64.28571428571422,
					-8.571428571428612
				],
				[
					71.42857142857144,
					-8.571428571428612
				],
				[
					78.57142857142856,
					-7.142857142857167
				],
				[
					82.85714285714289,
					-7.142857142857167
				],
				[
					85.71428571428567,
					-7.142857142857167
				],
				[
					87.14285714285711,
					-7.142857142857167
				],
				[
					88.57142857142856,
					-7.142857142857167
				],
				[
					90,
					-7.142857142857167
				],
				[
					90,
					-7.142857142857167
				],
				[
					111.42857142857144,
					-7.142857142857167
				],
				[
					134.28571428571422,
					-7.142857142857167
				],
				[
					141.42857142857144,
					-7.142857142857167
				],
				[
					145.71428571428567,
					-7.142857142857167
				],
				[
					147.1428571428571,
					-5.714285714285722
				],
				[
					145.71428571428567,
					-1.4285714285714448
				],
				[
					142.8571428571429,
					8.571428571428555
				],
				[
					142.8571428571429,
					18.571428571428555
				],
				[
					142.8571428571429,
					27.14285714285711
				],
				[
					142.8571428571429,
					30
				],
				[
					144.28571428571422,
					32.85714285714283
				],
				[
					145.71428571428567,
					32.85714285714283
				],
				[
					145.71428571428567,
					32.85714285714283
				],
				[
					152.8571428571429,
					32.85714285714283
				],
				[
					160,
					32.85714285714283
				],
				[
					161.42857142857144,
					32.85714285714283
				],
				[
					161.42857142857144,
					32.85714285714283
				],
				[
					162.8571428571429,
					34.28571428571428
				],
				[
					161.42857142857144,
					37.14285714285711
				],
				[
					154.28571428571422,
					41.42857142857139
				],
				[
					147.1428571428571,
					45.714285714285666
				],
				[
					140,
					50
				],
				[
					135.71428571428567,
					51.428571428571445
				],
				[
					137.1428571428571,
					52.85714285714289
				],
				[
					138.57142857142856,
					54.285714285714334
				],
				[
					144.28571428571422,
					55.714285714285666
				],
				[
					151.42857142857144,
					55.714285714285666
				],
				[
					155.71428571428567,
					55.714285714285666
				],
				[
					158.57142857142856,
					55.714285714285666
				],
				[
					158.57142857142856,
					55.714285714285666
				],
				[
					151.42857142857144,
					58.571428571428555
				],
				[
					142.8571428571429,
					61.428571428571445
				],
				[
					135.71428571428567,
					64.28571428571433
				],
				[
					138.57142857142856,
					65.71428571428567
				],
				[
					147.1428571428571,
					65.71428571428567
				],
				[
					154.28571428571422,
					68.57142857142856
				],
				[
					160,
					70
				],
				[
					162.8571428571429,
					70
				],
				[
					164.28571428571422,
					71.42857142857144
				],
				[
					164.28571428571422,
					71.42857142857144
				],
				[
					164.28571428571422,
					72.85714285714289
				],
				[
					164.28571428571422,
					77.14285714285711
				],
				[
					165.71428571428567,
					84.28571428571422
				],
				[
					165.71428571428567,
					87.14285714285711
				],
				[
					167.1428571428571,
					92.85714285714289
				],
				[
					167.1428571428571,
					95.71428571428567
				],
				[
					167.1428571428571,
					98.57142857142856
				],
				[
					167.1428571428571,
					101.42857142857144
				],
				[
					168.57142857142856,
					104.28571428571422
				],
				[
					167.1428571428571,
					107.14285714285711
				],
				[
					168.57142857142856,
					107.14285714285711
				],
				[
					172.8571428571429,
					104.28571428571422
				],
				[
					188.57142857142856,
					102.85714285714289
				],
				[
					192.8571428571429,
					101.42857142857144
				],
				[
					194.28571428571422,
					101.42857142857144
				],
				[
					190,
					102.85714285714289
				],
				[
					182.8571428571429,
					104.28571428571422
				],
				[
					178.57142857142856,
					105.71428571428567
				],
				[
					174.28571428571422,
					105.71428571428567
				],
				[
					168.57142857142856,
					107.14285714285711
				],
				[
					167.1428571428571,
					107.14285714285711
				],
				[
					165.71428571428567,
					107.14285714285711
				],
				[
					164.28571428571422,
					107.14285714285711
				],
				[
					157.1428571428571,
					107.14285714285711
				],
				[
					152.8571428571429,
					107.14285714285711
				],
				[
					151.42857142857144,
					107.14285714285711
				],
				[
					150,
					108.57142857142856
				],
				[
					150,
					108.57142857142856
				],
				[
					150,
					108.57142857142856
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 55,
			"versionNonce": 272045838,
			"isDeleted": false,
			"id": "iYBIvKVJrgvtKsLFXlQ1N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 226.12481962481917,
			"y": 577.9047619047619,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.428571428571445,
			"height": 4.285714285714334,
			"seed": 1819753746,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					1.4285714285714448
				],
				[
					-1.4285714285714448,
					2.8571428571428896
				],
				[
					-2.8571428571428896,
					2.8571428571428896
				],
				[
					-5.714285714285779,
					2.8571428571428896
				],
				[
					-10,
					2.8571428571428896
				],
				[
					-17.14285714285711,
					2.8571428571428896
				],
				[
					-18.571428571428555,
					2.8571428571428896
				],
				[
					-21.428571428571445,
					4.285714285714334
				],
				[
					-21.428571428571445,
					4.285714285714334
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 48,
			"versionNonce": 62138578,
			"isDeleted": false,
			"id": "aqSqoX9ii4LHQb2G7et6C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 224.69624819624772,
			"y": 587.9047619047619,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 127364174,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 177,
			"versionNonce": 1604126030,
			"isDeleted": false,
			"id": "mwrbSca00EQ2svtKv-fWu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 184.69624819624772,
			"y": 456.47619047619054,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 232.8571428571429,
			"height": 240,
			"seed": 1567043790,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					2.8571428571428896,
					0
				],
				[
					7.14285714285711,
					0
				],
				[
					12.85714285714289,
					0
				],
				[
					20,
					1.4285714285714448
				],
				[
					25.714285714285666,
					2.857142857142833
				],
				[
					31.428571428571445,
					2.857142857142833
				],
				[
					37.14285714285711,
					4.285714285714278
				],
				[
					41.428571428571445,
					4.285714285714278
				],
				[
					44.285714285714334,
					5.714285714285722
				],
				[
					45.714285714285666,
					5.714285714285722
				],
				[
					47.14285714285711,
					7.142857142857167
				],
				[
					48.571428571428555,
					7.142857142857167
				],
				[
					50,
					7.142857142857167
				],
				[
					52.85714285714289,
					7.142857142857167
				],
				[
					54.285714285714334,
					7.142857142857167
				],
				[
					54.285714285714334,
					7.142857142857167
				],
				[
					55.714285714285666,
					7.142857142857167
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					60,
					2.857142857142833
				],
				[
					62.85714285714289,
					5.714285714285722
				],
				[
					67.14285714285711,
					11.428571428571445
				],
				[
					70,
					17.142857142857167
				],
				[
					74.28571428571433,
					24.285714285714278
				],
				[
					75.71428571428567,
					27.142857142857167
				],
				[
					80,
					22.857142857142833
				],
				[
					82.85714285714289,
					14.285714285714278
				],
				[
					82.85714285714289,
					8.571428571428555
				],
				[
					82.85714285714289,
					7.142857142857167
				],
				[
					82.85714285714289,
					5.714285714285722
				],
				[
					84.28571428571433,
					4.285714285714278
				],
				[
					87.14285714285711,
					7.142857142857167
				],
				[
					88.57142857142856,
					8.571428571428555
				],
				[
					90,
					10
				],
				[
					90,
					11.428571428571445
				],
				[
					90,
					11.428571428571445
				],
				[
					92.85714285714289,
					10
				],
				[
					95.71428571428567,
					7.142857142857167
				],
				[
					98.57142857142856,
					0
				],
				[
					100,
					-5.714285714285722
				],
				[
					100,
					-12.857142857142833
				],
				[
					101.42857142857144,
					-8.571428571428555
				],
				[
					101.42857142857144,
					-2.857142857142833
				],
				[
					102.85714285714289,
					0
				],
				[
					102.85714285714289,
					1.4285714285714448
				],
				[
					102.85714285714289,
					5.714285714285722
				],
				[
					102.85714285714289,
					7.142857142857167
				],
				[
					102.85714285714289,
					10
				],
				[
					102.85714285714289,
					12.857142857142833
				],
				[
					104.28571428571433,
					14.285714285714278
				],
				[
					105.71428571428567,
					15.714285714285722
				],
				[
					108.57142857142856,
					15.714285714285722
				],
				[
					115.71428571428567,
					15.714285714285722
				],
				[
					125.71428571428567,
					15.714285714285722
				],
				[
					134.28571428571433,
					15.714285714285722
				],
				[
					137.1428571428571,
					15.714285714285722
				],
				[
					138.57142857142856,
					15.714285714285722
				],
				[
					140,
					15.714285714285722
				],
				[
					144.28571428571433,
					15.714285714285722
				],
				[
					147.1428571428571,
					15.714285714285722
				],
				[
					151.42857142857144,
					15.714285714285722
				],
				[
					152.8571428571429,
					15.714285714285722
				],
				[
					154.28571428571433,
					17.142857142857167
				],
				[
					154.28571428571433,
					21.428571428571445
				],
				[
					154.28571428571433,
					27.142857142857167
				],
				[
					154.28571428571433,
					34.28571428571428
				],
				[
					154.28571428571433,
					40
				],
				[
					154.28571428571433,
					44.28571428571428
				],
				[
					154.28571428571433,
					47.14285714285717
				],
				[
					154.28571428571433,
					51.428571428571445
				],
				[
					155.71428571428567,
					55.71428571428572
				],
				[
					157.1428571428571,
					60.00000000000006
				],
				[
					157.1428571428571,
					65.71428571428572
				],
				[
					157.1428571428571,
					70.00000000000006
				],
				[
					157.1428571428571,
					74.28571428571428
				],
				[
					158.57142857142856,
					80.00000000000006
				],
				[
					158.57142857142856,
					82.85714285714283
				],
				[
					158.57142857142856,
					88.57142857142861
				],
				[
					160,
					92.85714285714283
				],
				[
					160,
					95.71428571428572
				],
				[
					161.42857142857144,
					97.14285714285717
				],
				[
					161.42857142857144,
					98.57142857142861
				],
				[
					161.42857142857144,
					100.00000000000006
				],
				[
					161.42857142857144,
					102.85714285714283
				],
				[
					161.42857142857144,
					104.28571428571428
				],
				[
					161.42857142857144,
					108.57142857142861
				],
				[
					161.42857142857144,
					111.42857142857139
				],
				[
					161.42857142857144,
					118.57142857142861
				],
				[
					161.42857142857144,
					122.85714285714283
				],
				[
					161.42857142857144,
					127.14285714285717
				],
				[
					161.42857142857144,
					130.00000000000006
				],
				[
					161.42857142857144,
					131.4285714285714
				],
				[
					160,
					132.85714285714283
				],
				[
					160,
					134.28571428571428
				],
				[
					160,
					137.14285714285717
				],
				[
					160,
					138.5714285714286
				],
				[
					158.57142857142856,
					140.00000000000006
				],
				[
					158.57142857142856,
					147.14285714285717
				],
				[
					157.1428571428571,
					157.14285714285717
				],
				[
					157.1428571428571,
					168.5714285714286
				],
				[
					157.1428571428571,
					187.14285714285717
				],
				[
					157.1428571428571,
					197.14285714285717
				],
				[
					157.1428571428571,
					204.28571428571428
				],
				[
					155.71428571428567,
					210.00000000000006
				],
				[
					155.71428571428567,
					212.85714285714283
				],
				[
					155.71428571428567,
					214.28571428571428
				],
				[
					154.28571428571433,
					215.71428571428572
				],
				[
					154.28571428571433,
					215.71428571428572
				],
				[
					154.28571428571433,
					217.14285714285717
				],
				[
					154.28571428571433,
					218.5714285714286
				],
				[
					154.28571428571433,
					221.4285714285714
				],
				[
					155.71428571428567,
					222.85714285714283
				],
				[
					157.1428571428571,
					224.28571428571428
				],
				[
					157.1428571428571,
					225.71428571428572
				],
				[
					158.57142857142856,
					227.14285714285717
				],
				[
					160,
					227.14285714285717
				],
				[
					165.71428571428567,
					225.71428571428572
				],
				[
					185.71428571428567,
					221.4285714285714
				],
				[
					194.28571428571433,
					220.00000000000006
				],
				[
					202.8571428571429,
					218.5714285714286
				],
				[
					204.28571428571433,
					218.5714285714286
				],
				[
					205.71428571428567,
					218.5714285714286
				],
				[
					212.8571428571429,
					218.5714285714286
				],
				[
					214.28571428571433,
					218.5714285714286
				],
				[
					217.1428571428571,
					218.5714285714286
				],
				[
					220,
					218.5714285714286
				],
				[
					221.42857142857144,
					218.5714285714286
				],
				[
					222.8571428571429,
					218.5714285714286
				],
				[
					224.28571428571433,
					218.5714285714286
				],
				[
					230,
					217.14285714285717
				],
				[
					232.8571428571429,
					215.71428571428572
				],
				[
					232.8571428571429,
					215.71428571428572
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "rectangle",
			"version": 131,
			"versionNonce": 949698194,
			"isDeleted": false,
			"id": "0d73qcpW-qhERdibuNGPA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -423.8751803751807,
			"y": 286.4761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1038.571428571429,
			"height": 1398.5714285714282,
			"seed": 1370118226,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 548088718,
			"isDeleted": false,
			"id": "KLEyVtb8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 254.69624819624767,
			"y": 398.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 25,
			"seed": 810576658,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Ry",
			"rawText": "Ry",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 1939446866,
			"isDeleted": false,
			"id": "oW18y4mO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 148.981962481962,
			"y": 503.19047619047626,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 25,
			"seed": 192313806,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R3",
			"rawText": "R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 1637517774,
			"isDeleted": false,
			"id": "HccO0hNv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -38.160894660895224,
			"y": 604.6190476190476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 25,
			"seed": 772258386,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i = o",
			"rawText": "i = o",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 78,
			"versionNonce": 42353170,
			"isDeleted": false,
			"id": "ex9XOJ3P",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -16.446608946609558,
			"y": 703.9761904761906,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 25,
			"seed": 176286354,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i = o",
			"rawText": "i = o",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 25436174,
			"isDeleted": false,
			"id": "bCSSnE45",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -76.73232323232378,
			"y": 626.047619047619,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 118,
			"height": 25,
			"seed": 202744594,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "delta V = 0",
			"rawText": "delta V = 0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 1616392146,
			"isDeleted": false,
			"id": "AeWSCc4o",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -358.16089466089534,
			"y": 953.1904761904765,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 339,
			"height": 74,
			"seed": 1359912974,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "nodal @ 0\n(0- Vi )/R1 + (0-V )/R2 + 0 = 0\n-Vi/R1 = V/R2 ==> V = -R2/R1 * Vi",
			"rawText": "nodal @ 0\n(0- Vi )/R1 + (0-V )/R2 + 0 = 0\n-Vi/R1 = V/R2 ==> V = -R2/R1 * Vi",
			"baseline": 67,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 110,
			"versionNonce": 341896782,
			"isDeleted": false,
			"id": "pcaN4g72",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -355.3037518037525,
			"y": 1093.1904761904766,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 347,
			"height": 74,
			"seed": 551079566,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "nodal @ V\nv-0/R2 + V-0/R2 + V-V0 / Ry = 0\nV0/Ry = V (1/R2 + 1/R3 + 1/Ry)",
			"rawText": "nodal @ V\nv-0/R2 + V-0/R2 + V-V0 / Ry = 0\nV0/Ry = V (1/R2 + 1/R3 + 1/Ry)",
			"baseline": 67,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 73,
			"versionNonce": 287729042,
			"isDeleted": false,
			"id": "WSQy1EyL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 313.26767676767656,
			"y": 1003.1904761904767,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 170,
			"height": 25,
			"seed": 1817913486,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "it aint Ry its R4",
			"rawText": "it aint Ry its R4",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 127,
			"versionNonce": 1191834766,
			"isDeleted": false,
			"id": "F9A8jTcy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -355.3037518037522,
			"y": 1220.3333333333337,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 394,
			"height": 74,
			"seed": 1637262674,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0/Ry = -R2/R1 Vi (1/R2 + 1/R3 + 1/Ry)\n\n",
			"rawText": "V0/Ry = -R2/R1 Vi (1/R2 + 1/R3 + 1/Ry)\n\n",
			"baseline": 67,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 2116543314,
			"isDeleted": false,
			"id": "uD9OuxSN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -336.73232323232367,
			"y": 1420.333333333334,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 217,
			"height": 223,
			"seed": 1042845138,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [
				"P8jvvNMHgrC5lvRRCfJGD"
			],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "question\nR1 = 1k ohm\nRy = 100k\nR2 = R3 = 10K\nfind gain:\n\n-10(1+100/10 + 100/10)\n-10(1+10+10)\n-210",
			"rawText": "question\nR1 = 1k ohm\nRy = 100k\nR2 = R3 = 10K\nfind gain:\n\n-10(1+100/10 + 100/10)\n-10(1+10+10)\n-210",
			"baseline": 216,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 1127756494,
			"isDeleted": false,
			"id": "DPtYsHmw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -346.73232323232367,
			"y": 1293.1904761904766,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 342,
			"height": 25,
			"seed": 751915666,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [
				"P8jvvNMHgrC5lvRRCfJGD"
			],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0 = -R2/R1 (1+Ry/R3 + Ry/R2)Vi ",
			"rawText": "V0 = -R2/R1 (1+Ry/R3 + Ry/R2)Vi ",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "arrow",
			"version": 94,
			"versionNonce": 1370728722,
			"isDeleted": false,
			"id": "P8jvvNMHgrC5lvRRCfJGD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -5.303751803752107,
			"y": 1323.6190476190482,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 131.42857142857144,
			"height": 250,
			"seed": 1275873042,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": {
				"elementId": "nhwZ3m9NCsZV_HBp6i440",
				"focus": -0.9513194405646502,
				"gap": 5.4285714285715585
			},
			"endBinding": {
				"elementId": "ENwsTdcOtCWJq6PwV-V3S",
				"focus": 0.6346537149707204,
				"gap": 25.857142857143003
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
					42.85714285714289,
					188.57142857142867
				],
				[
					-88.57142857142856,
					250
				]
			]
		},
		{
			"type": "text",
			"version": 105,
			"versionNonce": 327461134,
			"isDeleted": false,
			"id": "ffitzty7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 56.124819624819565,
			"y": 1881.771557271557,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 249,
			"height": 42,
			"seed": 164208974,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 33.70656370656372,
			"fontFamily": 1,
			"text": "Classifying gain",
			"rawText": "Classifying gain",
			"baseline": 30,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "rectangle",
			"version": 84,
			"versionNonce": 1396750034,
			"isDeleted": false,
			"id": "URZpbEahh_GELX1wKrtG9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -423.87518037518055,
			"y": 1772.1904761904761,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1242.8571428571431,
			"height": 535.7142857142858,
			"seed": 1085669010,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 95,
			"versionNonce": 124278606,
			"isDeleted": false,
			"id": "INJEa0MaLGG7-N1UvINTb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -247.24193568273654,
			"y": 2208.9183196012596,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 91.4098260604199,
			"height": 2.611709316011959,
			"seed": 1612196754,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					0.6093988404027995,
					0.6093988404027999,
					0.5
				],
				[
					0.8705697720040089,
					0
				],
				[
					1.7411395440080177,
					0
				],
				[
					3.4822790880160355,
					0
				],
				[
					9.57626749204403,
					0
				],
				[
					13.929116352064002,
					0
				],
				[
					19.15253498408799,
					0
				],
				[
					22.63481407210402,
					0
				],
				[
					26.117093160119975,
					0
				],
				[
					28.72880247613203,
					0
				],
				[
					30.469942020139964,
					0
				],
				[
					31.34051179214397,
					0
				],
				[
					32.211081564147975,
					0
				],
				[
					33.95222110815602,
					0.8705697720038014
				],
				[
					36.563930424167964,
					0.8705697720038014
				],
				[
					40.046209512183985,
					1.7411395440078807
				],
				[
					43.528488600199964,
					1.7411395440078807
				],
				[
					47.010767688215964,
					2.611709316011959
				],
				[
					53.10475609224398,
					2.611709316011959
				],
				[
					63.55159335629201,
					2.611709316011959
				],
				[
					75.73957016434795,
					2.611709316011959
				],
				[
					85.31583765639188,
					2.611709316011959
				],
				[
					91.4098260604199,
					2.611709316011959
				],
				[
					91.4098260604199,
					2.611709316011959
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 81,
			"versionNonce": 1130761362,
			"isDeleted": false,
			"id": "vRyaVVkm2BiBDDSPtr2GJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -221.99541229462062,
			"y": 2229.8119941293544,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 47.88133746021995,
			"height": 0.6093988404027997,
			"seed": 37349774,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					0.6093988404027996,
					0.6093988404027997,
					0.5
				],
				[
					0.8705697720040098,
					0
				],
				[
					2.611709316012029,
					0
				],
				[
					6.093988404027997,
					0
				],
				[
					16.540825668076042,
					0
				],
				[
					28.72880247613203,
					0
				],
				[
					39.17563974018001,
					0
				],
				[
					46.140197916212024,
					0
				],
				[
					47.88133746021995,
					0
				],
				[
					47.88133746021995,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 80,
			"versionNonce": 389823886,
			"isDeleted": false,
			"id": "lMfdve9tyjvLR8aNYijX9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -207.19572617055277,
			"y": 2262.2685092346373,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.92911635206401,
			"height": 2.3505383844109558,
			"seed": 1260555026,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					-1.116003313134961
				],
				[
					0.6093988404027999,
					-0.5066044727321615,
					0.5
				],
				[
					0.8705697720040098,
					-1.116003313134961
				],
				[
					5.223418632023987,
					-1.9865730851390386
				],
				[
					9.576267492043963,
					-1.9865730851390386
				],
				[
					12.187976808055998,
					-1.9865730851390386
				],
				[
					13.058546580060009,
					-1.9865730851390386
				],
				[
					13.92911635206401,
					-2.857142857143117
				],
				[
					13.92911635206401,
					-2.857142857143117
				],
				[
					13.92911635206401,
					-2.857142857143117
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 109,
			"versionNonce": 937077330,
			"isDeleted": false,
			"id": "GilzWIh37I2vMnujLRsFa",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -197.5082942859892,
			"y": 2278.9810947876267,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.5739570164348065,
			"height": 108.56005056889855,
			"seed": 1678729170,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					-4.464013252539437,
					-69.19220541436114
				],
				[
					-3.8546144121366375,
					-68.58280657395834,
					0.5
				],
				[
					-4.464013252539437,
					-70.933344958369
				],
				[
					-4.464013252539437,
					-75.28619381838912
				],
				[
					-4.464013252539437,
					-86.60360085444105
				],
				[
					-4.464013252539437,
					-98.79157766249705
				],
				[
					-4.464013252539437,
					-110.97955447055303
				],
				[
					-4.464013252539437,
					-111.85012424255707
				],
				[
					-4.464013252539437,
					-114.46183355856907
				],
				[
					-4.464013252539437,
					-118.8146824185889
				],
				[
					-5.334583024543445,
					-124.0381010506131
				],
				[
					-6.2051527965474556,
					-128.3909499106329
				],
				[
					-6.2051527965474556,
					-131.87322899864898
				],
				[
					-7.075722568551464,
					-133.61436854265685
				],
				[
					-7.075722568551464,
					-135.355508086665
				],
				[
					-7.075722568551464,
					-136.22607785866904
				],
				[
					-7.946292340555407,
					-142.32006626269708
				],
				[
					-8.816862112559413,
					-144.93177557870908
				],
				[
					-8.816862112559413,
					-148.41405466672504
				],
				[
					-9.687431884563422,
					-150.15519421073293
				],
				[
					-9.687431884563422,
					-151.02576398273703
				],
				[
					-9.687431884563422,
					-151.89633375474082
				],
				[
					-9.687431884563422,
					-152.7669035267449
				],
				[
					-9.687431884563422,
					-155.3786128427569
				],
				[
					-10.558001656567432,
					-157.11975238676501
				],
				[
					-10.558001656567432,
					-158.86089193077288
				],
				[
					-10.558001656567432,
					-161.47260124678482
				],
				[
					-10.558001656567432,
					-164.95488033480092
				],
				[
					-10.558001656567432,
					-166.69601987880904
				],
				[
					-10.558001656567432,
					-167.56658965081283
				],
				[
					-10.558001656567432,
					-170.17829896682477
				],
				[
					-10.558001656567432,
					-172.79000828283708
				],
				[
					-10.558001656567432,
					-174.5311478268449
				],
				[
					-10.558001656567432,
					-175.40171759884896
				],
				[
					-10.558001656567432,
					-176.27228737085278
				],
				[
					-11.428571428571445,
					-177.14285714285688
				],
				[
					-11.428571428571445,
					-177.14285714285688
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "ellipse",
			"version": 94,
			"versionNonce": 1211718606,
			"isDeleted": false,
			"id": "_t2WA1feIcN2Ym5lJNBIB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -249.85364499874862,
			"y": 2003.4638534083142,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 73.99843062033997,
			"height": 96.63324469244387,
			"seed": 609330894,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 95,
			"versionNonce": 2004193298,
			"isDeleted": false,
			"id": "J4o1ByA1yV5d6FdqR9nsF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -174.36168806950178,
			"y": 2058.1754798959496,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.8204804045508,
			"height": 22.634814072104103,
			"seed": 1538799630,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					-20.64606129299488,
					-3.3480099394045233
				],
				[
					-20.036662452592086,
					-2.7386110990017234,
					0.5
				],
				[
					-21.516631064998894,
					-4.218579711408323
				],
				[
					-22.38720083700291,
					-5.959719255416481
				],
				[
					-24.12834038101092,
					-7.700858799424361
				],
				[
					-25.869479925018876,
					-7.700858799424361
				],
				[
					-26.740049697022883,
					-8.571428571428442
				],
				[
					-31.96346832904687,
					-3.3480099394045233
				],
				[
					-35.44574741706291,
					0.13426914861151482
				],
				[
					-38.05745673307487,
					2.7459784646234726
				],
				[
					-39.79859627708289,
					6.22825755263951
				],
				[
					-40.6691660490869,
					7.969397096647663
				],
				[
					-40.6691660490869,
					9.710536640655544
				],
				[
					-40.6691660490869,
					11.45167618466342
				],
				[
					-41.53973582109093,
					12.322245956667503
				],
				[
					-42.41030559309492,
					13.192815728671583
				],
				[
					-43.28087536509885,
					14.063385500675663
				],
				[
					-44.151445137102876,
					14.063385500675663
				],
				[
					-46.763154453114886,
					11.45167618466342
				],
				[
					-49.37486376912686,
					8.83996686865147
				],
				[
					-51.11600331313487,
					7.098827324643585
				],
				[
					-51.986573085138865,
					5.357687780635427
				],
				[
					-52.85714285714289,
					4.487118008631633
				],
				[
					-52.85714285714289,
					3.6165482366275503
				],
				[
					-52.85714285714289,
					3.6165482366275503
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 145,
			"versionNonce": 276345358,
			"isDeleted": false,
			"id": "Il_AgkCrt6uwRVN9lt3Rb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -219.3837029786087,
			"y": 2020.7619047619046,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 320.3696760974718,
			"height": 28.72880247613198,
			"seed": 1102884050,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					-17.298051353590264
				],
				[
					0.6093988404027997,
					-16.688652513187467,
					0.5
				],
				[
					0,
					-18.168621125594203
				],
				[
					0.8705697720040093,
					-20.780330441606296
				],
				[
					1.7411395440080186,
					-22.521469985614182
				],
				[
					1.7411395440080186,
					-23.392039757618267
				],
				[
					1.7411395440080186,
					-25.133179301626136
				],
				[
					1.7411395440080186,
					-26.003749073630217
				],
				[
					1.7411395440080186,
					-27.74488861763825
				],
				[
					1.7411395440080186,
					-28.615458389642185
				],
				[
					1.7411395440080186,
					-28.615458389642185
				],
				[
					1.7411395440080186,
					-29.486028161646264
				],
				[
					1.7411395440080186,
					-32.097737477658214
				],
				[
					1.7411395440080186,
					-32.968307249662296
				],
				[
					2.6117093160119587,
					-34.709446793670196
				],
				[
					6.093988404027996,
					-34.709446793670196
				],
				[
					29.599372248135985,
					-33.83887702166625
				],
				[
					51.36361654823592,
					-33.83887702166625
				],
				[
					75.73957016434794,
					-33.83887702166625
				],
				[
					100.11552378045991,
					-33.83887702166625
				],
				[
					119.26805876454789,
					-33.83887702166625
				],
				[
					135.80888443262393,
					-33.83887702166625
				],
				[
					151.4791403286959,
					-33.83887702166625
				],
				[
					164.53768690875594,
					-32.968307249662296
				],
				[
					173.24338462879584,
					-32.968307249662296
				],
				[
					174.98452417280387,
					-32.097737477658214
				],
				[
					176.72566371681182,
					-32.968307249662296
				],
				[
					177.5962334888159,
					-33.83887702166625
				],
				[
					178.46680326081992,
					-34.709446793670196
				],
				[
					178.46680326081992,
					-35.58001656567427
				],
				[
					178.46680326081992,
					-34.709446793670196
				],
				[
					179.33737303282382,
					-32.968307249662296
				],
				[
					181.0785125768319,
					-30.356597933650196
				],
				[
					182.81965212083983,
					-26.8743188456343
				],
				[
					185.4313614368519,
					-21.65090021361024
				],
				[
					187.17250098085992,
					-18.168621125594203
				],
				[
					188.04307075286374,
					-16.427481581586186
				],
				[
					188.913640524868,
					-15.556911809582244
				],
				[
					192.39591961288394,
					-19.03919089759815
				],
				[
					195.00762892889588,
					-24.262609529622203
				],
				[
					199.36047778891594,
					-31.22716770565414
				],
				[
					202.8427568769319,
					-38.191725881686224
				],
				[
					203.7133266489358,
					-40.80343519769818
				],
				[
					204.5838964209398,
					-39.062295653690306
				],
				[
					204.5838964209398,
					-37.32115610968214
				],
				[
					205.45446619294384,
					-32.968307249662296
				],
				[
					206.3250359649479,
					-28.615458389642185
				],
				[
					207.19560573695193,
					-26.003749073630217
				],
				[
					207.19560573695193,
					-22.521469985614182
				],
				[
					208.06617550895587,
					-20.780330441606296
				],
				[
					211.5484545969718,
					-22.521469985614182
				],
				[
					215.90130345699208,
					-26.8743188456343
				],
				[
					224.607001177032,
					-38.191725881686224
				],
				[
					227.218710493044,
					-42.5445747417062
				],
				[
					228.95985003705198,
					-44.28571428571422
				],
				[
					229.83041980905605,
					-40.80343519769818
				],
				[
					229.83041980905605,
					-39.062295653690306
				],
				[
					231.57155935306383,
					-34.709446793670196
				],
				[
					232.442129125068,
					-29.486028161646264
				],
				[
					232.442129125068,
					-26.8743188456343
				],
				[
					232.442129125068,
					-26.003749073630217
				],
				[
					235.05383844108005,
					-31.22716770565414
				],
				[
					236.79497798508797,
					-36.45058633767821
				],
				[
					238.536117529096,
					-39.93286542569424
				],
				[
					239.40668730109985,
					-41.674004969702246
				],
				[
					239.40668730109985,
					-42.5445747417062
				],
				[
					241.147826845108,
					-42.5445747417062
				],
				[
					244.63010593312399,
					-42.5445747417062
				],
				[
					255.947512969176,
					-42.5445747417062
				],
				[
					270.747199093244,
					-42.5445747417062
				],
				[
					290.77030384933596,
					-42.5445747417062
				],
				[
					309.05226906141996,
					-42.5445747417062
				],
				[
					317.75796678145986,
					-42.5445747417062
				],
				[
					320.3696760974718,
					-42.5445747417062
				],
				[
					320.3696760974718,
					-42.5445747417062
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1445838290,
			"isDeleted": false,
			"id": "1QbDMXhN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -40.04632994578476,
			"y": 2018.0023686007826,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 76,
			"height": 15,
			"seed": 2003318478,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 12.187976808055994,
			"fontFamily": 1,
			"text": "Rs (r series)",
			"rawText": "Rs (r series)",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 989020238,
			"isDeleted": false,
			"id": "zIXOnvlr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -343.87518037518055,
			"y": 2047.601740848916,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89,
			"height": 15,
			"seed": 205448590,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 12.187976808055993,
			"fontFamily": 1,
			"text": "Voltage source",
			"rawText": "Voltage source",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 62,
			"versionNonce": 286929810,
			"isDeleted": false,
			"id": "_JlNf313wFNkOyCilhYVW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 460.41053391053407,
			"y": 2165.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 116.71428571428567,
			"height": 15.28571428571422,
			"seed": 1428168466,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2.8571428571428896,
					-1.4285714285711038
				],
				[
					-10,
					-1.4285714285711038
				],
				[
					-34.285714285714334,
					-5.714285714285779
				],
				[
					-64.28571428571433,
					-10
				],
				[
					-94.28571428571433,
					-14.28571428571422
				],
				[
					-111.42857142857144,
					-14.28571428571422
				],
				[
					-115.71428571428567,
					-14.28571428571422
				],
				[
					-115.71428571428567,
					-14.28571428571422
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 72,
			"versionNonce": 1266812558,
			"isDeleted": false,
			"id": "oEsTvrNFJoTTiinHX8oSS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 421.8391053391055,
			"y": 2185.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 56.71428571428578,
			"height": 2.4285714285711038,
			"seed": 420508626,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-5.714285714285779,
					0
				],
				[
					-14.285714285714334,
					0
				],
				[
					-22.85714285714289,
					0
				],
				[
					-28.571428571428555,
					-1.4285714285711038
				],
				[
					-30,
					-1.4285714285711038
				],
				[
					-31.428571428571445,
					-1.4285714285711038
				],
				[
					-35.71428571428578,
					-1.4285714285711038
				],
				[
					-41.428571428571445,
					-1.4285714285711038
				],
				[
					-44.285714285714334,
					-1.4285714285711038
				],
				[
					-47.14285714285711,
					-1.4285714285711038
				],
				[
					-50,
					-1.4285714285711038
				],
				[
					-52.85714285714289,
					-1.4285714285711038
				],
				[
					-54.285714285714334,
					-1.4285714285711038
				],
				[
					-54.285714285714334,
					-1.4285714285711038
				],
				[
					-55.71428571428578,
					-1.4285714285711038
				],
				[
					-55.71428571428578,
					-1.4285714285711038
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 59,
			"versionNonce": 712110418,
			"isDeleted": false,
			"id": "9SEb_3Wb1h1fJW_7Mca0d",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 393.26767676767696,
			"y": 2215.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.428571428571445,
			"height": 2.4285714285711038,
			"seed": 1583691090,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					-1.4285714285711038
				],
				[
					-8.571428571428555,
					-1.4285714285711038
				],
				[
					-10,
					-1.4285714285711038
				],
				[
					-11.428571428571445,
					-1.4285714285711038
				],
				[
					-11.428571428571445,
					-1.4285714285711038
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 71,
			"versionNonce": 1658717390,
			"isDeleted": false,
			"id": "POZ2aCjexWkTiBgNKEHVb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 394.6962481962484,
			"y": 2155.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 55.28571428571422,
			"seed": 58706830,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1.4285714285711038
				],
				[
					0,
					-4.285714285714221
				],
				[
					0,
					-8.571428571428442
				],
				[
					0,
					-15.71428571428578
				],
				[
					0,
					-18.57142857142844
				],
				[
					0,
					-21.428571428571104
				],
				[
					0,
					-24.28571428571422
				],
				[
					0,
					-31.428571428571104
				],
				[
					0,
					-37.14285714285734
				],
				[
					0,
					-40
				],
				[
					0,
					-41.428571428571104
				],
				[
					0,
					-42.85714285714266
				],
				[
					0,
					-47.14285714285734
				],
				[
					0,
					-50
				],
				[
					0,
					-52.85714285714266
				],
				[
					0,
					-54.28571428571422
				],
				[
					0,
					-54.28571428571422
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "ellipse",
			"version": 79,
			"versionNonce": 1166800658,
			"isDeleted": false,
			"id": "m39rEdIJq8ytgmKcGSbZ3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 357.5533910533912,
			"y": 2006.4761904761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 74.28571428571433,
			"height": 95.71428571428578,
			"seed": 1789849618,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 86,
			"versionNonce": 580926222,
			"isDeleted": false,
			"id": "wvoF2RlVZtEiluoN-FuQZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 401.8391053391054,
			"y": 2077.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.571428571428555,
			"height": 51.42857142857156,
			"seed": 2016516942,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					1.4285714285715585
				],
				[
					-1.4285714285714448,
					1.4285714285715585
				],
				[
					-4.285714285714334,
					-1.4285714285711038
				],
				[
					-5.714285714285666,
					-4.285714285714221
				],
				[
					-5.714285714285666,
					-8.571428571428442
				],
				[
					-5.714285714285666,
					-12.857142857142662
				],
				[
					-5.714285714285666,
					-18.57142857142844
				],
				[
					-5.714285714285666,
					-22.857142857142662
				],
				[
					-5.714285714285666,
					-24.28571428571422
				],
				[
					-5.714285714285666,
					-25.714285714285325
				],
				[
					-5.714285714285666,
					-27.142857142856883
				],
				[
					-5.714285714285666,
					-28.57142857142844
				],
				[
					-7.14285714285711,
					-34.28571428571422
				],
				[
					-7.14285714285711,
					-35.714285714285325
				],
				[
					-7.14285714285711,
					-37.14285714285688
				],
				[
					-7.14285714285711,
					-38.57142857142844
				],
				[
					-7.14285714285711,
					-40
				],
				[
					-7.14285714285711,
					-41.428571428571104
				],
				[
					-7.14285714285711,
					-42.85714285714266
				],
				[
					-7.14285714285711,
					-44.28571428571422
				],
				[
					-7.14285714285711,
					-47.14285714285688
				],
				[
					-7.14285714285711,
					-48.57142857142844
				],
				[
					-8.571428571428555,
					-50
				],
				[
					-8.571428571428555,
					-50
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 81,
			"versionNonce": 48186578,
			"isDeleted": false,
			"id": "F0n4H5ydWFJn-Vr-_8RVD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 381.8391053391054,
			"y": 2045.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27.142857142857224,
			"height": 23.857142857142662,
			"seed": 1640160398,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.4285714285714448,
					-2.8571428571426623
				],
				[
					2.8571428571428896,
					-5.7142857142853245
				],
				[
					5.714285714285779,
					-8.571428571428442
				],
				[
					7.142857142857224,
					-12.857142857142662
				],
				[
					7.142857142857224,
					-14.28571428571422
				],
				[
					8.571428571428669,
					-17.142857142856883
				],
				[
					10,
					-18.57142857142844
				],
				[
					11.428571428571445,
					-21.428571428571104
				],
				[
					12.85714285714289,
					-22.857142857142662
				],
				[
					17.142857142857224,
					-18.57142857142844
				],
				[
					20,
					-15.714285714285325
				],
				[
					22.85714285714289,
					-12.857142857142662
				],
				[
					25.71428571428578,
					-11.428571428571104
				],
				[
					27.142857142857224,
					-11.428571428571104
				],
				[
					27.142857142857224,
					-10
				],
				[
					27.142857142857224,
					-10
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 159,
			"versionNonce": 289515854,
			"isDeleted": false,
			"id": "rm8lJM6e0X_Lz2-bHnnz2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 386.12481962481985,
			"y": 1997.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 142.85714285714278,
			"height": 217.14285714285734,
			"seed": 151019090,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					-4.285714285714221
				],
				[
					0,
					-10
				],
				[
					0,
					-14.28571428571422
				],
				[
					0,
					-22.857142857142662
				],
				[
					0,
					-25.714285714285552
				],
				[
					0,
					-27.14285714285711
				],
				[
					0,
					-28.57142857142844
				],
				[
					0,
					-30
				],
				[
					0,
					-32.85714285714266
				],
				[
					0,
					-35.71428571428555
				],
				[
					0,
					-38.57142857142844
				],
				[
					0,
					-40
				],
				[
					0,
					-42.85714285714266
				],
				[
					54.28571428571422,
					-40
				],
				[
					82.85714285714278,
					-35.71428571428555
				],
				[
					94.28571428571422,
					-35.71428571428555
				],
				[
					95.71428571428567,
					-35.71428571428555
				],
				[
					97.14285714285711,
					-35.71428571428555
				],
				[
					100,
					-35.71428571428555
				],
				[
					108.57142857142856,
					-35.71428571428555
				],
				[
					114.28571428571422,
					-35.71428571428555
				],
				[
					117.14285714285711,
					-35.71428571428555
				],
				[
					118.57142857142856,
					-27.14285714285711
				],
				[
					118.57142857142856,
					-21.42857142857133
				],
				[
					118.57142857142856,
					-14.28571428571422
				],
				[
					118.57142857142856,
					-8.571428571428442
				],
				[
					118.57142857142856,
					-2.8571428571426623
				],
				[
					118.57142857142856,
					2.8571428571428896
				],
				[
					118.57142857142856,
					4.285714285714448
				],
				[
					118.57142857142856,
					5.714285714285779
				],
				[
					118.57142857142856,
					8.571428571428669
				],
				[
					118.57142857142856,
					10
				],
				[
					118.57142857142856,
					11.428571428571558
				],
				[
					118.57142857142856,
					12.85714285714289
				],
				[
					118.57142857142856,
					18.57142857142844
				],
				[
					118.57142857142856,
					21.42857142857156
				],
				[
					118.57142857142856,
					22.857142857143117
				],
				[
					118.57142857142856,
					27.142857142857338
				],
				[
					118.57142857142856,
					28.57142857142844
				],
				[
					118.57142857142856,
					30
				],
				[
					118.57142857142856,
					31.42857142857156
				],
				[
					118.57142857142856,
					32.85714285714312
				],
				[
					118.57142857142856,
					32.85714285714312
				],
				[
					118.57142857142856,
					34.28571428571422
				],
				[
					117.14285714285711,
					35.71428571428578
				],
				[
					108.57142857142856,
					37.14285714285734
				],
				[
					104.28571428571422,
					38.57142857142844
				],
				[
					98.57142857142856,
					38.57142857142844
				],
				[
					97.14285714285711,
					40
				],
				[
					95.71428571428567,
					40
				],
				[
					95.71428571428567,
					41.42857142857156
				],
				[
					102.85714285714278,
					44.28571428571422
				],
				[
					114.28571428571422,
					50
				],
				[
					125.71428571428567,
					51.42857142857156
				],
				[
					138.57142857142856,
					54.28571428571422
				],
				[
					141.42857142857133,
					55.71428571428578
				],
				[
					142.85714285714278,
					57.14285714285734
				],
				[
					138.57142857142856,
					57.14285714285734
				],
				[
					131.42857142857133,
					58.57142857142844
				],
				[
					124.28571428571422,
					58.57142857142844
				],
				[
					110,
					61.42857142857156
				],
				[
					102.85714285714278,
					62.85714285714312
				],
				[
					101.42857142857133,
					64.28571428571422
				],
				[
					102.85714285714278,
					64.28571428571422
				],
				[
					108.57142857142856,
					67.14285714285734
				],
				[
					117.14285714285711,
					68.57142857142844
				],
				[
					124.28571428571422,
					71.42857142857156
				],
				[
					125.71428571428567,
					71.42857142857156
				],
				[
					127.14285714285711,
					72.85714285714312
				],
				[
					127.14285714285711,
					74.28571428571422
				],
				[
					124.28571428571422,
					77.14285714285734
				],
				[
					121.42857142857133,
					78.57142857142844
				],
				[
					115.71428571428567,
					81.42857142857156
				],
				[
					111.42857142857133,
					82.85714285714312
				],
				[
					110,
					84.28571428571422
				],
				[
					111.42857142857133,
					85.71428571428578
				],
				[
					112.85714285714278,
					87.14285714285734
				],
				[
					114.28571428571422,
					88.57142857142844
				],
				[
					115.71428571428567,
					92.85714285714312
				],
				[
					118.57142857142856,
					98.57142857142844
				],
				[
					121.42857142857133,
					101.42857142857156
				],
				[
					122.85714285714278,
					107.14285714285734
				],
				[
					122.85714285714278,
					110
				],
				[
					122.85714285714278,
					114.28571428571468
				],
				[
					124.28571428571422,
					121.42857142857156
				],
				[
					124.28571428571422,
					124.28571428571468
				],
				[
					124.28571428571422,
					127.14285714285734
				],
				[
					124.28571428571422,
					131.42857142857156
				],
				[
					124.28571428571422,
					135.71428571428578
				],
				[
					124.28571428571422,
					140
				],
				[
					124.28571428571422,
					144.28571428571468
				],
				[
					124.28571428571422,
					148.57142857142844
				],
				[
					124.28571428571422,
					155.71428571428578
				],
				[
					124.28571428571422,
					158.57142857142844
				],
				[
					124.28571428571422,
					161.42857142857156
				],
				[
					125.71428571428567,
					164.28571428571468
				],
				[
					127.14285714285711,
					167.14285714285734
				],
				[
					127.14285714285711,
					168.57142857142844
				],
				[
					127.14285714285711,
					170
				],
				[
					127.14285714285711,
					171.42857142857156
				],
				[
					127.14285714285711,
					172.85714285714312
				],
				[
					127.14285714285711,
					174.28571428571468
				],
				[
					127.14285714285711,
					174.28571428571468
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 1543690898,
			"isDeleted": false,
			"id": "pzHwW8zy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 530.410533910534,
			"y": 2040.3333333333335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 25,
			"seed": 1407066446,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rp",
			"rawText": "Rp",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 56,
			"versionNonce": 2115719054,
			"isDeleted": false,
			"id": "Oq_kUm0QJOPh0cAXOmHtl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 510.41053391053407,
			"y": 2170.761904761905,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 1260119570,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 57,
			"versionNonce": 2142091346,
			"isDeleted": false,
			"id": "jZMnN6PUjFREIto5JnnqG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 507.5533910533912,
			"y": 2166.476190476191,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.857142857142776,
			"height": 1,
			"seed": 1740195730,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-2.857142857142776,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 73,
			"versionNonce": 1701195214,
			"isDeleted": false,
			"id": "3poKM0PiUc8bywAcSKKaS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 510.41053391053407,
			"y": 2167.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89.57142857142856,
			"height": 29.57142857142844,
			"seed": 1286657166,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-2.8571428571428896,
					-1.4285714285711038
				],
				[
					-8.571428571428555,
					-4.285714285713766
				],
				[
					-18.571428571428555,
					-10
				],
				[
					-22.85714285714289,
					-12.857142857142662
				],
				[
					-28.571428571428555,
					-15.714285714285325
				],
				[
					-30,
					-15.714285714285325
				],
				[
					-31.428571428571445,
					-17.142857142856883
				],
				[
					-32.85714285714289,
					-18.57142857142844
				],
				[
					-38.571428571428555,
					-18.57142857142844
				],
				[
					-47.14285714285711,
					-20
				],
				[
					-52.85714285714289,
					-21.428571428571104
				],
				[
					-57.14285714285711,
					-21.428571428571104
				],
				[
					-58.571428571428555,
					-22.857142857142662
				],
				[
					-60,
					-22.857142857142662
				],
				[
					-68.57142857142856,
					-24.285714285713766
				],
				[
					-77.14285714285711,
					-25.714285714285325
				],
				[
					-84.28571428571433,
					-27.142857142856883
				],
				[
					-87.14285714285711,
					-28.57142857142844
				],
				[
					-88.57142857142856,
					-28.57142857142844
				],
				[
					-88.57142857142856,
					-28.57142857142844
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 74,
			"versionNonce": 766959122,
			"isDeleted": false,
			"id": "l9_Xh7E5Y_BMVMZTnz5hS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 387.5533910533912,
			"y": 2135.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.71428571428578,
			"height": 8.571428571428896,
			"seed": 359529106,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1.4285714285715585
				],
				[
					1.4285714285714448,
					2.8571428571426623
				],
				[
					4.285714285714334,
					2.8571428571426623
				],
				[
					5.714285714285779,
					4.285714285714221
				],
				[
					8.571428571428555,
					5.714285714285779
				],
				[
					10,
					5.714285714285779
				],
				[
					10,
					5.714285714285779
				],
				[
					11.428571428571445,
					7.142857142857338
				],
				[
					12.85714285714289,
					7.142857142857338
				],
				[
					14.285714285714334,
					7.142857142857338
				],
				[
					17.142857142857224,
					7.142857142857338
				],
				[
					18.571428571428555,
					7.142857142857338
				],
				[
					21.428571428571445,
					8.571428571428896
				],
				[
					22.85714285714289,
					8.571428571428896
				],
				[
					24.285714285714334,
					8.571428571428896
				],
				[
					24.285714285714334,
					8.571428571428896
				],
				[
					25.71428571428578,
					8.571428571428896
				],
				[
					31.428571428571445,
					8.571428571428896
				],
				[
					40,
					8.571428571428896
				],
				[
					45.71428571428578,
					5.714285714285779
				],
				[
					45.71428571428578,
					5.714285714285779
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1413170190,
			"isDeleted": false,
			"id": "thKgraCI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 210.41053391053407,
			"y": 2047.4761904761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 146,
			"height": 25,
			"seed": 1645423954,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Current source",
			"rawText": "Current source",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 113,
			"versionNonce": 320162770,
			"isDeleted": false,
			"id": "N12vEAX3kiB7zieQAVmbr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 171.83910533910534,
			"y": 1952.1904761904755,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.285714285714214,
			"height": 335.7142857142856,
			"seed": 1590761934,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					10.603829160530196,
					0
				],
				[
					12.42857142857144,
					0.45454545454545436,
					0.5
				],
				[
					5.390279823269651,
					5.194805194805149
				],
				[
					2.7835051546392755,
					17.53246753246757
				],
				[
					0.17673048600889807,
					28.571428571428577
				],
				[
					0.17673048600889807,
					39.61038961038958
				],
				[
					0.17673048600889807,
					51.298701298701296
				],
				[
					-10.250368188512606,
					66.88311688311684
				],
				[
					-10.250368188512606,
					83.76623376623381
				],
				[
					-10.250368188512606,
					106.49350649350653
				],
				[
					-10.250368188512606,
					127.92207792207783
				],
				[
					-10.250368188512606,
					144.15584415584408
				],
				[
					-10.250368188512606,
					153.89610389610388
				],
				[
					-10.250368188512606,
					164.28571428571416
				],
				[
					-10.250368188512606,
					177.92207792207782
				],
				[
					-10.250368188512606,
					193.50649350649357
				],
				[
					-12.857142857142776,
					211.68831168831173
				],
				[
					-12.857142857142776,
					220.1298701298701
				],
				[
					-12.857142857142776,
					225.97402597402586
				],
				[
					-12.857142857142776,
					230.51948051948042
				],
				[
					-12.857142857142776,
					234.41558441558445
				],
				[
					-12.857142857142776,
					238.961038961039
				],
				[
					-12.857142857142776,
					244.80519480519476
				],
				[
					-10.250368188512606,
					248.70129870129858
				],
				[
					-10.250368188512606,
					249.9999999999998
				],
				[
					-10.250368188512606,
					251.29870129870122
				],
				[
					-7.643593519882231,
					251.94805194805193
				],
				[
					-7.643593519882231,
					255.19480519480504
				],
				[
					-7.643593519882231,
					259.0909090909089
				],
				[
					-5.036818851251853,
					269.4805194805194
				],
				[
					-5.036818851251853,
					274.02597402597394
				],
				[
					-2.4300441826214776,
					279.2207792207792
				],
				[
					-2.4300441826214776,
					289.61038961038946
				],
				[
					-2.4300441826214776,
					295.4545454545452
				],
				[
					-2.4300441826214776,
					300.6493506493505
				],
				[
					-2.4300441826214776,
					303.8961038961038
				],
				[
					-2.4300441826214776,
					308.44155844155836
				],
				[
					-2.4300441826214776,
					311.03896103896096
				],
				[
					-2.4300441826214776,
					312.3376623376622
				],
				[
					-2.4300441826214776,
					314.2857142857141
				],
				[
					-2.4300441826214776,
					316.23376623376623
				],
				[
					-2.4300441826214776,
					317.5324675324674
				],
				[
					2.7835051546392755,
					323.37662337662323
				],
				[
					2.7835051546392755,
					326.62337662337654
				],
				[
					2.7835051546392755,
					328.57142857142844
				],
				[
					2.7835051546392755,
					331.8181818181816
				],
				[
					2.7835051546392755,
					335.0649350649349
				],
				[
					2.7835051546392755,
					335.7142857142856
				],
				[
					2.7835051546392755,
					335.7142857142856
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "rectangle",
			"version": 84,
			"versionNonce": 1284739662,
			"isDeleted": false,
			"id": "Zn4h32Hd-Eanfmrnh1020",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -426.7323232323237,
			"y": 2393.6190476190477,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1260.0000000000002,
			"height": 572.8571428571427,
			"seed": 1775639566,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "text",
			"version": 143,
			"versionNonce": 635437458,
			"isDeleted": false,
			"id": "L3Li0O0y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -245.30375180375233,
			"y": 2568.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 198,
			"seed": 426301202,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Voltage gain\n\nAv = V0 / Vi (V/V)\n\n\nCurrent gain\n\nAi = I0/Ii(A/A)",
			"rawText": "Voltage gain\n\nAv = V0 / Vi (V/V)\n\n\nCurrent gain\n\nAi = I0/Ii(A/A)",
			"baseline": 191,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 692590734,
			"isDeleted": false,
			"id": "0y5pnXdI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 253.2676767676764,
			"y": 2590.333333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 170,
			"height": 50,
			"seed": 1652974094,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Gain impedence\nAim = V0/Ii (V/A)",
			"rawText": "Gain impedence\nAim = V0/Ii (V/A)",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 21888850,
			"isDeleted": false,
			"id": "JC9mH6Oe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -63.37518037518083,
			"y": 2568.261904761905,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 79,
			"height": 25,
			"seed": 1789717906,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Amplifier",
			"rawText": "Amplifier",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 73,
			"versionNonce": 34723534,
			"isDeleted": false,
			"id": "2BzZBiu7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -66.23232323232372,
			"y": 2713.9761904761904,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 79,
			"height": 25,
			"seed": 377894286,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Amplifier",
			"rawText": "Amplifier",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 1102464274,
			"isDeleted": false,
			"id": "DrxRqYDX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 459.4819624819622,
			"y": 2596.8333333333326,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 79,
			"height": 25,
			"seed": 607725006,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Amplifier",
			"rawText": "Amplifier",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 260689166,
			"isDeleted": false,
			"id": "ITCwj8st",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 263.2676767676764,
			"y": 2694.6190476190473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 208,
			"height": 74,
			"seed": 1170775570,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Conductunce Amplifier\n\nAcn = i0/Vi (A/V)",
			"rawText": "Conductunce Amplifier\n\nAcn = i0/Vi (A/V)",
			"baseline": 67,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 144,
			"versionNonce": 93951698,
			"isDeleted": false,
			"id": "9Xh0TTmN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -81.73232323232367,
			"y": 2449.5816993464055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 530,
			"height": 87,
			"seed": 2081615634,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 69.17273576097111,
			"fontFamily": 1,
			"text": "4 types of gain",
			"rawText": "4 types of gain",
			"baseline": 62,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 62,
			"versionNonce": 254344014,
			"isDeleted": false,
			"id": "Rdc2MqXm6tJw48M1kK-gL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -203.94660894660956,
			"y": 3386.833333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 116.71428571428567,
			"height": 15.28571428571422,
			"seed": 1004129682,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2.8571428571428896,
					-1.4285714285711038
				],
				[
					-10,
					-1.4285714285711038
				],
				[
					-34.285714285714334,
					-5.714285714285779
				],
				[
					-64.28571428571433,
					-10
				],
				[
					-94.28571428571433,
					-14.28571428571422
				],
				[
					-111.42857142857144,
					-14.28571428571422
				],
				[
					-115.71428571428567,
					-14.28571428571422
				],
				[
					-115.71428571428567,
					-14.28571428571422
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 72,
			"versionNonce": 275884178,
			"isDeleted": false,
			"id": "JNb853-0GECCZ2_0wnmdc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -242.5180375180381,
			"y": 3406.833333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 56.71428571428578,
			"height": 2.4285714285711038,
			"seed": 1637944462,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-5.714285714285779,
					0
				],
				[
					-14.285714285714334,
					0
				],
				[
					-22.85714285714289,
					0
				],
				[
					-28.571428571428555,
					-1.4285714285711038
				],
				[
					-30,
					-1.4285714285711038
				],
				[
					-31.428571428571445,
					-1.4285714285711038
				],
				[
					-35.71428571428578,
					-1.4285714285711038
				],
				[
					-41.428571428571445,
					-1.4285714285711038
				],
				[
					-44.285714285714334,
					-1.4285714285711038
				],
				[
					-47.14285714285711,
					-1.4285714285711038
				],
				[
					-50,
					-1.4285714285711038
				],
				[
					-52.85714285714289,
					-1.4285714285711038
				],
				[
					-54.285714285714334,
					-1.4285714285711038
				],
				[
					-54.285714285714334,
					-1.4285714285711038
				],
				[
					-55.71428571428578,
					-1.4285714285711038
				],
				[
					-55.71428571428578,
					-1.4285714285711038
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 59,
			"versionNonce": 659054990,
			"isDeleted": false,
			"id": "awAg599RcYKN6KIZw8wIo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -271.08946608946667,
			"y": 3436.833333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.428571428571445,
			"height": 2.4285714285711038,
			"seed": 1311656786,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					-1.4285714285711038
				],
				[
					-8.571428571428555,
					-1.4285714285711038
				],
				[
					-10,
					-1.4285714285711038
				],
				[
					-11.428571428571445,
					-1.4285714285711038
				],
				[
					-11.428571428571445,
					-1.4285714285711038
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 71,
			"versionNonce": 420660818,
			"isDeleted": false,
			"id": "U-qn3q8jZSW0nGaf2grUD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -269.6608946608952,
			"y": 3376.833333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 55.28571428571422,
			"seed": 724323022,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1.4285714285711038
				],
				[
					0,
					-4.285714285714221
				],
				[
					0,
					-8.571428571428442
				],
				[
					0,
					-15.71428571428578
				],
				[
					0,
					-18.57142857142844
				],
				[
					0,
					-21.428571428571104
				],
				[
					0,
					-24.28571428571422
				],
				[
					0,
					-31.428571428571104
				],
				[
					0,
					-37.14285714285734
				],
				[
					0,
					-40
				],
				[
					0,
					-41.428571428571104
				],
				[
					0,
					-42.85714285714266
				],
				[
					0,
					-47.14285714285734
				],
				[
					0,
					-50
				],
				[
					0,
					-52.85714285714266
				],
				[
					0,
					-54.28571428571422
				],
				[
					0,
					-54.28571428571422
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "ellipse",
			"version": 79,
			"versionNonce": 1260453838,
			"isDeleted": false,
			"id": "_0yQxZEuLVcOUVpI68XfG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -306.80375180375245,
			"y": 3228.2619047619055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 74.28571428571433,
			"height": 95.71428571428578,
			"seed": 615321874,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 86,
			"versionNonce": 860498962,
			"isDeleted": false,
			"id": "CH2fjjlG4vdcOiilTUf6h",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -262.5180375180382,
			"y": 3299.690476190476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.571428571428555,
			"height": 51.42857142857156,
			"seed": 355844366,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					1.4285714285715585
				],
				[
					-1.4285714285714448,
					1.4285714285715585
				],
				[
					-4.285714285714334,
					-1.4285714285711038
				],
				[
					-5.714285714285666,
					-4.285714285714221
				],
				[
					-5.714285714285666,
					-8.571428571428442
				],
				[
					-5.714285714285666,
					-12.857142857142662
				],
				[
					-5.714285714285666,
					-18.57142857142844
				],
				[
					-5.714285714285666,
					-22.857142857142662
				],
				[
					-5.714285714285666,
					-24.28571428571422
				],
				[
					-5.714285714285666,
					-25.714285714285325
				],
				[
					-5.714285714285666,
					-27.142857142856883
				],
				[
					-5.714285714285666,
					-28.57142857142844
				],
				[
					-7.14285714285711,
					-34.28571428571422
				],
				[
					-7.14285714285711,
					-35.714285714285325
				],
				[
					-7.14285714285711,
					-37.14285714285688
				],
				[
					-7.14285714285711,
					-38.57142857142844
				],
				[
					-7.14285714285711,
					-40
				],
				[
					-7.14285714285711,
					-41.428571428571104
				],
				[
					-7.14285714285711,
					-42.85714285714266
				],
				[
					-7.14285714285711,
					-44.28571428571422
				],
				[
					-7.14285714285711,
					-47.14285714285688
				],
				[
					-7.14285714285711,
					-48.57142857142844
				],
				[
					-8.571428571428555,
					-50
				],
				[
					-8.571428571428555,
					-50
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 81,
			"versionNonce": 516675086,
			"isDeleted": false,
			"id": "2zv_dQx8Cte4AAJxvLAd_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -282.5180375180382,
			"y": 3266.833333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27.142857142857224,
			"height": 23.857142857142662,
			"seed": 1389174482,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.4285714285714448,
					-2.8571428571426623
				],
				[
					2.8571428571428896,
					-5.7142857142853245
				],
				[
					5.714285714285779,
					-8.571428571428442
				],
				[
					7.142857142857224,
					-12.857142857142662
				],
				[
					7.142857142857224,
					-14.28571428571422
				],
				[
					8.571428571428669,
					-17.142857142856883
				],
				[
					10,
					-18.57142857142844
				],
				[
					11.428571428571445,
					-21.428571428571104
				],
				[
					12.85714285714289,
					-22.857142857142662
				],
				[
					17.142857142857224,
					-18.57142857142844
				],
				[
					20,
					-15.714285714285325
				],
				[
					22.85714285714289,
					-12.857142857142662
				],
				[
					25.71428571428578,
					-11.428571428571104
				],
				[
					27.142857142857224,
					-11.428571428571104
				],
				[
					27.142857142857224,
					-10
				],
				[
					27.142857142857224,
					-10
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 159,
			"versionNonce": 1695472082,
			"isDeleted": false,
			"id": "mZ7ME3JU22gq_QAvJqn1P",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -278.2323232323238,
			"y": 3219.690476190476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 142.85714285714278,
			"height": 217.14285714285734,
			"seed": 1664511822,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					-4.285714285714221
				],
				[
					0,
					-10
				],
				[
					0,
					-14.28571428571422
				],
				[
					0,
					-22.857142857142662
				],
				[
					0,
					-25.714285714285552
				],
				[
					0,
					-27.14285714285711
				],
				[
					0,
					-28.57142857142844
				],
				[
					0,
					-30
				],
				[
					0,
					-32.85714285714266
				],
				[
					0,
					-35.71428571428555
				],
				[
					0,
					-38.57142857142844
				],
				[
					0,
					-40
				],
				[
					0,
					-42.85714285714266
				],
				[
					54.28571428571422,
					-40
				],
				[
					82.85714285714278,
					-35.71428571428555
				],
				[
					94.28571428571422,
					-35.71428571428555
				],
				[
					95.71428571428567,
					-35.71428571428555
				],
				[
					97.14285714285711,
					-35.71428571428555
				],
				[
					100,
					-35.71428571428555
				],
				[
					108.57142857142856,
					-35.71428571428555
				],
				[
					114.28571428571422,
					-35.71428571428555
				],
				[
					117.14285714285711,
					-35.71428571428555
				],
				[
					118.57142857142856,
					-27.14285714285711
				],
				[
					118.57142857142856,
					-21.42857142857133
				],
				[
					118.57142857142856,
					-14.28571428571422
				],
				[
					118.57142857142856,
					-8.571428571428442
				],
				[
					118.57142857142856,
					-2.8571428571426623
				],
				[
					118.57142857142856,
					2.8571428571428896
				],
				[
					118.57142857142856,
					4.285714285714448
				],
				[
					118.57142857142856,
					5.714285714285779
				],
				[
					118.57142857142856,
					8.571428571428669
				],
				[
					118.57142857142856,
					10
				],
				[
					118.57142857142856,
					11.428571428571558
				],
				[
					118.57142857142856,
					12.85714285714289
				],
				[
					118.57142857142856,
					18.57142857142844
				],
				[
					118.57142857142856,
					21.42857142857156
				],
				[
					118.57142857142856,
					22.857142857143117
				],
				[
					118.57142857142856,
					27.142857142857338
				],
				[
					118.57142857142856,
					28.57142857142844
				],
				[
					118.57142857142856,
					30
				],
				[
					118.57142857142856,
					31.42857142857156
				],
				[
					118.57142857142856,
					32.85714285714312
				],
				[
					118.57142857142856,
					32.85714285714312
				],
				[
					118.57142857142856,
					34.28571428571422
				],
				[
					117.14285714285711,
					35.71428571428578
				],
				[
					108.57142857142856,
					37.14285714285734
				],
				[
					104.28571428571422,
					38.57142857142844
				],
				[
					98.57142857142856,
					38.57142857142844
				],
				[
					97.14285714285711,
					40
				],
				[
					95.71428571428567,
					40
				],
				[
					95.71428571428567,
					41.42857142857156
				],
				[
					102.85714285714278,
					44.28571428571422
				],
				[
					114.28571428571422,
					50
				],
				[
					125.71428571428567,
					51.42857142857156
				],
				[
					138.57142857142856,
					54.28571428571422
				],
				[
					141.42857142857133,
					55.71428571428578
				],
				[
					142.85714285714278,
					57.14285714285734
				],
				[
					138.57142857142856,
					57.14285714285734
				],
				[
					131.42857142857133,
					58.57142857142844
				],
				[
					124.28571428571422,
					58.57142857142844
				],
				[
					110,
					61.42857142857156
				],
				[
					102.85714285714278,
					62.85714285714312
				],
				[
					101.42857142857133,
					64.28571428571422
				],
				[
					102.85714285714278,
					64.28571428571422
				],
				[
					108.57142857142856,
					67.14285714285734
				],
				[
					117.14285714285711,
					68.57142857142844
				],
				[
					124.28571428571422,
					71.42857142857156
				],
				[
					125.71428571428567,
					71.42857142857156
				],
				[
					127.14285714285711,
					72.85714285714312
				],
				[
					127.14285714285711,
					74.28571428571422
				],
				[
					124.28571428571422,
					77.14285714285734
				],
				[
					121.42857142857133,
					78.57142857142844
				],
				[
					115.71428571428567,
					81.42857142857156
				],
				[
					111.42857142857133,
					82.85714285714312
				],
				[
					110,
					84.28571428571422
				],
				[
					111.42857142857133,
					85.71428571428578
				],
				[
					112.85714285714278,
					87.14285714285734
				],
				[
					114.28571428571422,
					88.57142857142844
				],
				[
					115.71428571428567,
					92.85714285714312
				],
				[
					118.57142857142856,
					98.57142857142844
				],
				[
					121.42857142857133,
					101.42857142857156
				],
				[
					122.85714285714278,
					107.14285714285734
				],
				[
					122.85714285714278,
					110
				],
				[
					122.85714285714278,
					114.28571428571468
				],
				[
					124.28571428571422,
					121.42857142857156
				],
				[
					124.28571428571422,
					124.28571428571468
				],
				[
					124.28571428571422,
					127.14285714285734
				],
				[
					124.28571428571422,
					131.42857142857156
				],
				[
					124.28571428571422,
					135.71428571428578
				],
				[
					124.28571428571422,
					140
				],
				[
					124.28571428571422,
					144.28571428571468
				],
				[
					124.28571428571422,
					148.57142857142844
				],
				[
					124.28571428571422,
					155.71428571428578
				],
				[
					124.28571428571422,
					158.57142857142844
				],
				[
					124.28571428571422,
					161.42857142857156
				],
				[
					125.71428571428567,
					164.28571428571468
				],
				[
					127.14285714285711,
					167.14285714285734
				],
				[
					127.14285714285711,
					168.57142857142844
				],
				[
					127.14285714285711,
					170
				],
				[
					127.14285714285711,
					171.42857142857156
				],
				[
					127.14285714285711,
					172.85714285714312
				],
				[
					127.14285714285711,
					174.28571428571468
				],
				[
					127.14285714285711,
					174.28571428571468
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 1531044942,
			"isDeleted": false,
			"id": "OICKIKZc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.94660894660962,
			"y": 3262.1190476190477,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 25,
			"seed": 1696953490,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rp",
			"rawText": "Rp",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 56,
			"versionNonce": 1568133010,
			"isDeleted": false,
			"id": "X1EQmHTH1mk3TE09c2y9b",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.94660894660956,
			"y": 3392.5476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 25646478,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 57,
			"versionNonce": 844901006,
			"isDeleted": false,
			"id": "tpkuhxPCdLVq6T4n3_2C7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -156.80375180375245,
			"y": 3388.2619047619055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.857142857142776,
			"height": 1,
			"seed": 1030558290,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-2.857142857142776,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 73,
			"versionNonce": 1354501458,
			"isDeleted": false,
			"id": "EtxTxP4dRQhsWjlvhpxj4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.94660894660956,
			"y": 3389.690476190476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89.57142857142856,
			"height": 29.57142857142844,
			"seed": 1767994318,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-2.8571428571428896,
					-1.4285714285711038
				],
				[
					-8.571428571428555,
					-4.285714285713766
				],
				[
					-18.571428571428555,
					-10
				],
				[
					-22.85714285714289,
					-12.857142857142662
				],
				[
					-28.571428571428555,
					-15.714285714285325
				],
				[
					-30,
					-15.714285714285325
				],
				[
					-31.428571428571445,
					-17.142857142856883
				],
				[
					-32.85714285714289,
					-18.57142857142844
				],
				[
					-38.571428571428555,
					-18.57142857142844
				],
				[
					-47.14285714285711,
					-20
				],
				[
					-52.85714285714289,
					-21.428571428571104
				],
				[
					-57.14285714285711,
					-21.428571428571104
				],
				[
					-58.571428571428555,
					-22.857142857142662
				],
				[
					-60,
					-22.857142857142662
				],
				[
					-68.57142857142856,
					-24.285714285713766
				],
				[
					-77.14285714285711,
					-25.714285714285325
				],
				[
					-84.28571428571433,
					-27.142857142856883
				],
				[
					-87.14285714285711,
					-28.57142857142844
				],
				[
					-88.57142857142856,
					-28.57142857142844
				],
				[
					-88.57142857142856,
					-28.57142857142844
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 74,
			"versionNonce": 852732110,
			"isDeleted": false,
			"id": "BuHXxvWhgltpgzSZjf0pl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -276.80375180375245,
			"y": 3356.833333333333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.71428571428578,
			"height": 8.571428571428896,
			"seed": 1853552658,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1.4285714285715585
				],
				[
					1.4285714285714448,
					2.8571428571426623
				],
				[
					4.285714285714334,
					2.8571428571426623
				],
				[
					5.714285714285779,
					4.285714285714221
				],
				[
					8.571428571428555,
					5.714285714285779
				],
				[
					10,
					5.714285714285779
				],
				[
					10,
					5.714285714285779
				],
				[
					11.428571428571445,
					7.142857142857338
				],
				[
					12.85714285714289,
					7.142857142857338
				],
				[
					14.285714285714334,
					7.142857142857338
				],
				[
					17.142857142857224,
					7.142857142857338
				],
				[
					18.571428571428555,
					7.142857142857338
				],
				[
					21.428571428571445,
					8.571428571428896
				],
				[
					22.85714285714289,
					8.571428571428896
				],
				[
					24.285714285714334,
					8.571428571428896
				],
				[
					24.285714285714334,
					8.571428571428896
				],
				[
					25.71428571428578,
					8.571428571428896
				],
				[
					31.428571428571445,
					8.571428571428896
				],
				[
					40,
					8.571428571428896
				],
				[
					45.71428571428578,
					5.714285714285779
				],
				[
					45.71428571428578,
					5.714285714285779
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1412600594,
			"isDeleted": false,
			"id": "CpQxvoKv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -453.94660894660956,
			"y": 3269.2619047619055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 146,
			"height": 25,
			"seed": 81644046,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Current source",
			"rawText": "Current source",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 144,
			"versionNonce": 742481678,
			"isDeleted": false,
			"id": "y4ncEAlw-UT03HimJyvHy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 565.4462481962476,
			"y": 3190.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226,
			"height": 189,
			"seed": 535853006,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1
				],
				[
					1,
					5
				],
				[
					20,
					19
				],
				[
					62,
					44
				],
				[
					114,
					76
				],
				[
					160,
					110
				],
				[
					208,
					139
				],
				[
					215,
					143
				],
				[
					211,
					144
				],
				[
					186,
					148
				],
				[
					145,
					162
				],
				[
					95,
					168
				],
				[
					51,
					174
				],
				[
					30,
					177
				],
				[
					26,
					178
				],
				[
					26,
					179
				],
				[
					26,
					181
				],
				[
					21,
					185
				],
				[
					16,
					187
				],
				[
					13,
					188
				],
				[
					12,
					189
				],
				[
					11,
					187
				],
				[
					11,
					184
				],
				[
					11,
					179
				],
				[
					10,
					153
				],
				[
					10,
					127
				],
				[
					10,
					102
				],
				[
					5,
					83
				],
				[
					1,
					67
				],
				[
					0,
					61
				],
				[
					-3,
					52
				],
				[
					-6,
					42
				],
				[
					-9,
					30
				],
				[
					-10,
					24
				],
				[
					-11,
					19
				],
				[
					-11,
					18
				],
				[
					-11,
					16
				],
				[
					-11,
					14
				],
				[
					-11,
					10
				],
				[
					-11,
					5
				],
				[
					-11,
					2
				],
				[
					-11,
					0
				],
				[
					-11,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 109,
			"versionNonce": 978477266,
			"isDeleted": false,
			"id": "0o51tiOauWhILxbdezcE6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 544.4462481962476,
			"y": 3244.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206,
			"height": 5,
			"seed": 1867396114,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-45,
					0
				],
				[
					-105,
					-2
				],
				[
					-163,
					-2
				],
				[
					-200,
					-2
				],
				[
					-205,
					-4
				],
				[
					-205,
					-4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 109,
			"versionNonce": 320752974,
			"isDeleted": false,
			"id": "9vWKRB-tYpI4DpRU_PmYz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 345.44624819624755,
			"y": 3232.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 18,
			"seed": 451694094,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					2
				],
				[
					0,
					4
				],
				[
					-2,
					13
				],
				[
					-4,
					17
				],
				[
					-5,
					18
				],
				[
					-9,
					13
				],
				[
					-14,
					6
				],
				[
					-18,
					2
				],
				[
					-18,
					2
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 138,
			"versionNonce": 1857189522,
			"isDeleted": false,
			"id": "n2dRaWEIWq_7PxNDYTUja",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 326.44624819624755,
			"y": 3232.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 147,
			"height": 16,
			"seed": 324133330,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					1
				],
				[
					-2,
					4
				],
				[
					-2,
					8
				],
				[
					-3,
					10
				],
				[
					-4,
					14
				],
				[
					-4,
					15
				],
				[
					-5,
					16
				],
				[
					-5,
					14
				],
				[
					-6,
					13
				],
				[
					-8,
					8
				],
				[
					-9,
					6
				],
				[
					-10,
					4
				],
				[
					-10,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				],
				[
					-11,
					7
				],
				[
					-12,
					10
				],
				[
					-13,
					12
				],
				[
					-14,
					13
				],
				[
					-16,
					12
				],
				[
					-17,
					11
				],
				[
					-19,
					8
				],
				[
					-21,
					5
				],
				[
					-22,
					3
				],
				[
					-24,
					3
				],
				[
					-26,
					4
				],
				[
					-27,
					5
				],
				[
					-28,
					5
				],
				[
					-31,
					5
				],
				[
					-33,
					6
				],
				[
					-44,
					7
				],
				[
					-54,
					9
				],
				[
					-68,
					9
				],
				[
					-99,
					9
				],
				[
					-124,
					9
				],
				[
					-139,
					9
				],
				[
					-145,
					9
				],
				[
					-146,
					9
				],
				[
					-146,
					9
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 1690530702,
			"isDeleted": false,
			"id": "y5XdnODg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 317.44624819624755,
			"y": 3195.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 50,
			"seed": 1821596750,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r1\n",
			"rawText": "r1\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 133,
			"versionNonce": 1376375890,
			"isDeleted": false,
			"id": "kEfGIlMv9RIpIyoRktSv4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 572.4462481962476,
			"y": 3335.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 189,
			"height": 126,
			"seed": 1578751890,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8,
					1
				],
				[
					-21,
					1
				],
				[
					-65,
					5
				],
				[
					-107,
					11
				],
				[
					-142,
					14
				],
				[
					-174,
					14
				],
				[
					-184,
					14
				],
				[
					-186,
					14
				],
				[
					-187,
					14
				],
				[
					-188,
					15
				],
				[
					-188,
					29
				],
				[
					-184,
					42
				],
				[
					-182,
					56
				],
				[
					-181,
					67
				],
				[
					-181,
					77
				],
				[
					-181,
					84
				],
				[
					-181,
					93
				],
				[
					-181,
					99
				],
				[
					-181,
					104
				],
				[
					-180,
					107
				],
				[
					-180,
					108
				],
				[
					-180,
					108
				],
				[
					-180,
					109
				],
				[
					-180,
					110
				],
				[
					-180,
					112
				],
				[
					-180,
					114
				],
				[
					-180,
					116
				],
				[
					-180,
					118
				],
				[
					-180,
					122
				],
				[
					-180,
					123
				],
				[
					-180,
					124
				],
				[
					-181,
					126
				],
				[
					-182,
					126
				],
				[
					-182,
					126
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 107,
			"versionNonce": 191484366,
			"isDeleted": false,
			"id": "luEfwk_KFUXzTL624-5M1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 411.44624819624755,
			"y": 3458.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 7,
			"seed": 180265614,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1
				],
				[
					-2,
					-2
				],
				[
					-13,
					-2
				],
				[
					-27,
					-2
				],
				[
					-45,
					2
				],
				[
					-56,
					5
				],
				[
					-60,
					5
				],
				[
					-61,
					5
				],
				[
					-61,
					5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 102,
			"versionNonce": 372210194,
			"isDeleted": false,
			"id": "1mhQIk2q9Ocnx2WRBkvNK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 390.44624819624755,
			"y": 3477.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 4,
			"seed": 2145195346,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					0
				],
				[
					-8,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 105,
			"versionNonce": 1110075406,
			"isDeleted": false,
			"id": "PKFogtHYT86DoThYCwKmc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 403.44624819624755,
			"y": 3498.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 1,
			"seed": 1210523854,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-1,
					0
				],
				[
					-3,
					0
				],
				[
					-7,
					0
				],
				[
					-8,
					0
				],
				[
					-9,
					1
				],
				[
					-9,
					1
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 437938130,
			"isDeleted": false,
			"id": "wkNNWeKf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 591.4462481962476,
			"y": 3329.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 25,
			"seed": 166894354,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 2029925966,
			"isDeleted": false,
			"id": "X0LeGjCS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 585.4462481962476,
			"y": 3235.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 25,
			"seed": 946198286,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 100,
			"versionNonce": 1172413842,
			"isDeleted": false,
			"id": "OqXA2a0XOzsDXgWQL5PsU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 771.4462481962476,
			"y": 3328.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 1255237842,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 122,
			"versionNonce": 951991438,
			"isDeleted": false,
			"id": "fuP64NKcaC2Huq0nlx9rP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 768.4462481962476,
			"y": 3327.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 105,
			"height": 1,
			"seed": 334742862,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					4,
					0
				],
				[
					13,
					0
				],
				[
					37,
					0
				],
				[
					55,
					0
				],
				[
					62,
					0
				],
				[
					63,
					0
				],
				[
					64,
					0
				],
				[
					64,
					0
				],
				[
					66,
					0
				],
				[
					70,
					0
				],
				[
					71,
					0
				],
				[
					72,
					0
				],
				[
					73,
					0
				],
				[
					75,
					0
				],
				[
					78,
					0
				],
				[
					83,
					0
				],
				[
					89,
					0
				],
				[
					93,
					0
				],
				[
					98,
					0
				],
				[
					100,
					0
				],
				[
					103,
					0
				],
				[
					104,
					0
				],
				[
					105,
					0
				],
				[
					105,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1723603794,
			"isDeleted": false,
			"id": "VKzPczQP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 821.4462481962476,
			"y": 3290.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 25,
			"seed": 705724050,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "v0",
			"rawText": "v0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 99,
			"versionNonce": 119765710,
			"isDeleted": false,
			"id": "FrCFzTEX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 629.4462481962476,
			"y": 3283.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 25,
			"seed": 472509326,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A = inf",
			"rawText": "A = inf",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "line",
			"version": 187,
			"versionNonce": 184606994,
			"isDeleted": false,
			"id": "SVLsKKoIdMj7e-fZXtHDG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 446.94624819624755,
			"y": 3241.751984126984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127.14285714285717,
			"height": 131.4285714285714,
			"seed": 73849938,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
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
					-1.428571428571388,
					-125.71428571428567
				],
				[
					125.71428571428578,
					-131.4285714285714
				]
			]
		},
		{
			"type": "freedraw",
			"version": 185,
			"versionNonce": 1254551822,
			"isDeleted": false,
			"id": "B4b0jEHIb8gm6UVswyHVf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 571.231962481962,
			"y": 3107.46626984127,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 194.28571428571422,
			"height": 128.57142857142856,
			"seed": 2134985166,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					4.285714285714221,
					-2.8571428571428896
				],
				[
					8.571428571428555,
					-12.85714285714289
				],
				[
					10,
					-14.285714285714334
				],
				[
					11.428571428571445,
					-11.428571428571445
				],
				[
					11.428571428571445,
					-8.571428571428612
				],
				[
					14.28571428571422,
					0
				],
				[
					15.714285714285666,
					5.714285714285666
				],
				[
					17.14285714285711,
					10
				],
				[
					18.571428571428555,
					12.857142857142833
				],
				[
					18.571428571428555,
					14.285714285714278
				],
				[
					17.14285714285711,
					15.714285714285666
				],
				[
					15.714285714285666,
					4.285714285714278
				],
				[
					18.571428571428555,
					-7.142857142857167
				],
				[
					22.85714285714289,
					-15.714285714285722
				],
				[
					25.714285714285666,
					-20
				],
				[
					27.14285714285711,
					-18.571428571428612
				],
				[
					30,
					-11.428571428571445
				],
				[
					32.85714285714289,
					-5.714285714285722
				],
				[
					34.28571428571422,
					-2.8571428571428896
				],
				[
					34.28571428571422,
					-1.4285714285714448
				],
				[
					34.28571428571422,
					0
				],
				[
					35.714285714285666,
					-1.4285714285714448
				],
				[
					38.571428571428555,
					-5.714285714285722
				],
				[
					38.571428571428555,
					-8.571428571428612
				],
				[
					41.428571428571445,
					-15.714285714285722
				],
				[
					41.428571428571445,
					-18.571428571428612
				],
				[
					42.85714285714289,
					-20
				],
				[
					42.85714285714289,
					-17.142857142857167
				],
				[
					42.85714285714289,
					-12.85714285714289
				],
				[
					42.85714285714289,
					-8.571428571428612
				],
				[
					45.714285714285666,
					1.428571428571388
				],
				[
					45.714285714285666,
					4.285714285714278
				],
				[
					47.14285714285711,
					8.571428571428555
				],
				[
					48.571428571428555,
					11.428571428571388
				],
				[
					51.428571428571445,
					10
				],
				[
					52.85714285714289,
					8.571428571428555
				],
				[
					55.714285714285666,
					5.714285714285666
				],
				[
					57.14285714285711,
					5.714285714285666
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					58.571428571428555,
					2.857142857142833
				],
				[
					58.571428571428555,
					0
				],
				[
					58.571428571428555,
					-4.285714285714334
				],
				[
					58.571428571428555,
					-7.142857142857167
				],
				[
					58.571428571428555,
					-10
				],
				[
					60,
					-11.428571428571445
				],
				[
					64.28571428571422,
					-8.571428571428612
				],
				[
					71.42857142857144,
					-8.571428571428612
				],
				[
					78.57142857142856,
					-7.142857142857167
				],
				[
					82.85714285714289,
					-7.142857142857167
				],
				[
					85.71428571428567,
					-7.142857142857167
				],
				[
					87.14285714285711,
					-7.142857142857167
				],
				[
					88.57142857142856,
					-7.142857142857167
				],
				[
					90,
					-7.142857142857167
				],
				[
					90,
					-7.142857142857167
				],
				[
					111.42857142857144,
					-7.142857142857167
				],
				[
					134.28571428571422,
					-7.142857142857167
				],
				[
					141.42857142857144,
					-7.142857142857167
				],
				[
					145.71428571428567,
					-7.142857142857167
				],
				[
					147.1428571428571,
					-5.714285714285722
				],
				[
					145.71428571428567,
					-1.4285714285714448
				],
				[
					142.8571428571429,
					8.571428571428555
				],
				[
					142.8571428571429,
					18.571428571428555
				],
				[
					142.8571428571429,
					27.14285714285711
				],
				[
					142.8571428571429,
					30
				],
				[
					144.28571428571422,
					32.85714285714283
				],
				[
					145.71428571428567,
					32.85714285714283
				],
				[
					145.71428571428567,
					32.85714285714283
				],
				[
					152.8571428571429,
					32.85714285714283
				],
				[
					160,
					32.85714285714283
				],
				[
					161.42857142857144,
					32.85714285714283
				],
				[
					161.42857142857144,
					32.85714285714283
				],
				[
					162.8571428571429,
					34.28571428571428
				],
				[
					161.42857142857144,
					37.14285714285711
				],
				[
					154.28571428571422,
					41.42857142857139
				],
				[
					147.1428571428571,
					45.714285714285666
				],
				[
					140,
					50
				],
				[
					135.71428571428567,
					51.428571428571445
				],
				[
					137.1428571428571,
					52.85714285714289
				],
				[
					138.57142857142856,
					54.285714285714334
				],
				[
					144.28571428571422,
					55.714285714285666
				],
				[
					151.42857142857144,
					55.714285714285666
				],
				[
					155.71428571428567,
					55.714285714285666
				],
				[
					158.57142857142856,
					55.714285714285666
				],
				[
					158.57142857142856,
					55.714285714285666
				],
				[
					151.42857142857144,
					58.571428571428555
				],
				[
					142.8571428571429,
					61.428571428571445
				],
				[
					135.71428571428567,
					64.28571428571433
				],
				[
					138.57142857142856,
					65.71428571428567
				],
				[
					147.1428571428571,
					65.71428571428567
				],
				[
					154.28571428571422,
					68.57142857142856
				],
				[
					160,
					70
				],
				[
					162.8571428571429,
					70
				],
				[
					164.28571428571422,
					71.42857142857144
				],
				[
					164.28571428571422,
					71.42857142857144
				],
				[
					164.28571428571422,
					72.85714285714289
				],
				[
					164.28571428571422,
					77.14285714285711
				],
				[
					165.71428571428567,
					84.28571428571422
				],
				[
					165.71428571428567,
					87.14285714285711
				],
				[
					167.1428571428571,
					92.85714285714289
				],
				[
					167.1428571428571,
					95.71428571428567
				],
				[
					167.1428571428571,
					98.57142857142856
				],
				[
					167.1428571428571,
					101.42857142857144
				],
				[
					168.57142857142856,
					104.28571428571422
				],
				[
					167.1428571428571,
					107.14285714285711
				],
				[
					168.57142857142856,
					107.14285714285711
				],
				[
					172.8571428571429,
					104.28571428571422
				],
				[
					188.57142857142856,
					102.85714285714289
				],
				[
					192.8571428571429,
					101.42857142857144
				],
				[
					194.28571428571422,
					101.42857142857144
				],
				[
					190,
					102.85714285714289
				],
				[
					182.8571428571429,
					104.28571428571422
				],
				[
					178.57142857142856,
					105.71428571428567
				],
				[
					174.28571428571422,
					105.71428571428567
				],
				[
					168.57142857142856,
					107.14285714285711
				],
				[
					167.1428571428571,
					107.14285714285711
				],
				[
					165.71428571428567,
					107.14285714285711
				],
				[
					164.28571428571422,
					107.14285714285711
				],
				[
					157.1428571428571,
					107.14285714285711
				],
				[
					152.8571428571429,
					107.14285714285711
				],
				[
					151.42857142857144,
					107.14285714285711
				],
				[
					150,
					108.57142857142856
				],
				[
					150,
					108.57142857142856
				],
				[
					150,
					108.57142857142856
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 80,
			"versionNonce": 1579609810,
			"isDeleted": false,
			"id": "pks5KkvnKKqdGiR1V7a5w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 751.231962481962,
			"y": 3221.751984126984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.428571428571445,
			"height": 4.285714285714334,
			"seed": 128680466,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					1.4285714285714448
				],
				[
					-1.4285714285714448,
					2.8571428571428896
				],
				[
					-2.8571428571428896,
					2.8571428571428896
				],
				[
					-5.714285714285779,
					2.8571428571428896
				],
				[
					-10,
					2.8571428571428896
				],
				[
					-17.14285714285711,
					2.8571428571428896
				],
				[
					-18.571428571428555,
					2.8571428571428896
				],
				[
					-21.428571428571445,
					4.285714285714334
				],
				[
					-21.428571428571445,
					4.285714285714334
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 73,
			"versionNonce": 790732622,
			"isDeleted": false,
			"id": "T9jMdaItlXboFphwHVjoy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 749.8033910533904,
			"y": 3231.751984126984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 1012064270,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 80037010,
			"isDeleted": false,
			"id": "E51-0C_PK-kdaDEbMCO5u",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 709.8033910533904,
			"y": 3100.3234126984125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 232.8571428571429,
			"height": 240,
			"seed": 248868818,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					2.8571428571428896,
					0
				],
				[
					7.14285714285711,
					0
				],
				[
					12.85714285714289,
					0
				],
				[
					20,
					1.4285714285714448
				],
				[
					25.714285714285666,
					2.857142857142833
				],
				[
					31.428571428571445,
					2.857142857142833
				],
				[
					37.14285714285711,
					4.285714285714278
				],
				[
					41.428571428571445,
					4.285714285714278
				],
				[
					44.285714285714334,
					5.714285714285722
				],
				[
					45.714285714285666,
					5.714285714285722
				],
				[
					47.14285714285711,
					7.142857142857167
				],
				[
					48.571428571428555,
					7.142857142857167
				],
				[
					50,
					7.142857142857167
				],
				[
					52.85714285714289,
					7.142857142857167
				],
				[
					54.285714285714334,
					7.142857142857167
				],
				[
					54.285714285714334,
					7.142857142857167
				],
				[
					55.714285714285666,
					7.142857142857167
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					60,
					2.857142857142833
				],
				[
					62.85714285714289,
					5.714285714285722
				],
				[
					67.14285714285711,
					11.428571428571445
				],
				[
					70,
					17.142857142857167
				],
				[
					74.28571428571433,
					24.285714285714278
				],
				[
					75.71428571428567,
					27.142857142857167
				],
				[
					80,
					22.857142857142833
				],
				[
					82.85714285714289,
					14.285714285714278
				],
				[
					82.85714285714289,
					8.571428571428555
				],
				[
					82.85714285714289,
					7.142857142857167
				],
				[
					82.85714285714289,
					5.714285714285722
				],
				[
					84.28571428571433,
					4.285714285714278
				],
				[
					87.14285714285711,
					7.142857142857167
				],
				[
					88.57142857142856,
					8.571428571428555
				],
				[
					90,
					10
				],
				[
					90,
					11.428571428571445
				],
				[
					90,
					11.428571428571445
				],
				[
					92.85714285714289,
					10
				],
				[
					95.71428571428567,
					7.142857142857167
				],
				[
					98.57142857142856,
					0
				],
				[
					100,
					-5.714285714285722
				],
				[
					100,
					-12.857142857142833
				],
				[
					101.42857142857144,
					-8.571428571428555
				],
				[
					101.42857142857144,
					-2.857142857142833
				],
				[
					102.85714285714289,
					0
				],
				[
					102.85714285714289,
					1.4285714285714448
				],
				[
					102.85714285714289,
					5.714285714285722
				],
				[
					102.85714285714289,
					7.142857142857167
				],
				[
					102.85714285714289,
					10
				],
				[
					102.85714285714289,
					12.857142857142833
				],
				[
					104.28571428571433,
					14.285714285714278
				],
				[
					105.71428571428567,
					15.714285714285722
				],
				[
					108.57142857142856,
					15.714285714285722
				],
				[
					115.71428571428567,
					15.714285714285722
				],
				[
					125.71428571428567,
					15.714285714285722
				],
				[
					134.28571428571433,
					15.714285714285722
				],
				[
					137.1428571428571,
					15.714285714285722
				],
				[
					138.57142857142856,
					15.714285714285722
				],
				[
					140,
					15.714285714285722
				],
				[
					144.28571428571433,
					15.714285714285722
				],
				[
					147.1428571428571,
					15.714285714285722
				],
				[
					151.42857142857144,
					15.714285714285722
				],
				[
					152.8571428571429,
					15.714285714285722
				],
				[
					154.28571428571433,
					17.142857142857167
				],
				[
					154.28571428571433,
					21.428571428571445
				],
				[
					154.28571428571433,
					27.142857142857167
				],
				[
					154.28571428571433,
					34.28571428571428
				],
				[
					154.28571428571433,
					40
				],
				[
					154.28571428571433,
					44.28571428571428
				],
				[
					154.28571428571433,
					47.14285714285717
				],
				[
					154.28571428571433,
					51.428571428571445
				],
				[
					155.71428571428567,
					55.71428571428572
				],
				[
					157.1428571428571,
					60.00000000000006
				],
				[
					157.1428571428571,
					65.71428571428572
				],
				[
					157.1428571428571,
					70.00000000000006
				],
				[
					157.1428571428571,
					74.28571428571428
				],
				[
					158.57142857142856,
					80.00000000000006
				],
				[
					158.57142857142856,
					82.85714285714283
				],
				[
					158.57142857142856,
					88.57142857142861
				],
				[
					160,
					92.85714285714283
				],
				[
					160,
					95.71428571428572
				],
				[
					161.42857142857144,
					97.14285714285717
				],
				[
					161.42857142857144,
					98.57142857142861
				],
				[
					161.42857142857144,
					100.00000000000006
				],
				[
					161.42857142857144,
					102.85714285714283
				],
				[
					161.42857142857144,
					104.28571428571428
				],
				[
					161.42857142857144,
					108.57142857142861
				],
				[
					161.42857142857144,
					111.42857142857139
				],
				[
					161.42857142857144,
					118.57142857142861
				],
				[
					161.42857142857144,
					122.85714285714283
				],
				[
					161.42857142857144,
					127.14285714285717
				],
				[
					161.42857142857144,
					130.00000000000006
				],
				[
					161.42857142857144,
					131.4285714285714
				],
				[
					160,
					132.85714285714283
				],
				[
					160,
					134.28571428571428
				],
				[
					160,
					137.14285714285717
				],
				[
					160,
					138.5714285714286
				],
				[
					158.57142857142856,
					140.00000000000006
				],
				[
					158.57142857142856,
					147.14285714285717
				],
				[
					157.1428571428571,
					157.14285714285717
				],
				[
					157.1428571428571,
					168.5714285714286
				],
				[
					157.1428571428571,
					187.14285714285717
				],
				[
					157.1428571428571,
					197.14285714285717
				],
				[
					157.1428571428571,
					204.28571428571428
				],
				[
					155.71428571428567,
					210.00000000000006
				],
				[
					155.71428571428567,
					212.85714285714283
				],
				[
					155.71428571428567,
					214.28571428571428
				],
				[
					154.28571428571433,
					215.71428571428572
				],
				[
					154.28571428571433,
					215.71428571428572
				],
				[
					154.28571428571433,
					217.14285714285717
				],
				[
					154.28571428571433,
					218.5714285714286
				],
				[
					154.28571428571433,
					221.4285714285714
				],
				[
					155.71428571428567,
					222.85714285714283
				],
				[
					157.1428571428571,
					224.28571428571428
				],
				[
					157.1428571428571,
					225.71428571428572
				],
				[
					158.57142857142856,
					227.14285714285717
				],
				[
					160,
					227.14285714285717
				],
				[
					165.71428571428567,
					225.71428571428572
				],
				[
					185.71428571428567,
					221.4285714285714
				],
				[
					194.28571428571433,
					220.00000000000006
				],
				[
					202.8571428571429,
					218.5714285714286
				],
				[
					204.28571428571433,
					218.5714285714286
				],
				[
					205.71428571428567,
					218.5714285714286
				],
				[
					212.8571428571429,
					218.5714285714286
				],
				[
					214.28571428571433,
					218.5714285714286
				],
				[
					217.1428571428571,
					218.5714285714286
				],
				[
					220,
					218.5714285714286
				],
				[
					221.42857142857144,
					218.5714285714286
				],
				[
					222.8571428571429,
					218.5714285714286
				],
				[
					224.28571428571433,
					218.5714285714286
				],
				[
					230,
					217.14285714285717
				],
				[
					232.8571428571429,
					215.71428571428572
				],
				[
					232.8571428571429,
					215.71428571428572
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 67,
			"versionNonce": 143426958,
			"isDeleted": false,
			"id": "dwCZ367Q",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 674.0891053391048,
			"y": 3147.0376984126983,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 25,
			"seed": 123186766,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R3",
			"rawText": "R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 2022892114,
			"isDeleted": false,
			"id": "RB0BfGuM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 486.94624819624755,
			"y": 3248.46626984127,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 25,
			"seed": 2113643922,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i = o",
			"rawText": "i = o",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 943760334,
			"isDeleted": false,
			"id": "NPdLrelz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 508.6605339105332,
			"y": 3347.8234126984125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 25,
			"seed": 757642382,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i = o",
			"rawText": "i = o",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 1684457490,
			"isDeleted": false,
			"id": "StITv9h2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 448.374819624819,
			"y": 3269.894841269841,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 118,
			"height": 25,
			"seed": 508896082,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "delta V = 0",
			"rawText": "delta V = 0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 40,
			"versionNonce": 274135566,
			"isDeleted": false,
			"id": "AvKvReQVtEMBOwF5oz-4r",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 11.553391053390442,
			"y": 3275.3333333333335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 72,
			"height": 2,
			"seed": 129711826,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					2
				],
				[
					6,
					2
				],
				[
					22,
					2
				],
				[
					46,
					2
				],
				[
					60,
					2
				],
				[
					64,
					2
				],
				[
					66,
					2
				],
				[
					68,
					0
				],
				[
					68,
					0
				],
				[
					70,
					0
				],
				[
					70,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 41,
			"versionNonce": 3667410,
			"isDeleted": false,
			"id": "R6QFS8xCgBK6LkYK5BifM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 47.55339105339044,
			"y": 3233.3333333333335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 72,
			"seed": 2002123982,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					2
				],
				[
					-2,
					18
				],
				[
					-2,
					30
				],
				[
					-2,
					40
				],
				[
					-4,
					48
				],
				[
					-4,
					54
				],
				[
					-4,
					56
				],
				[
					-6,
					60
				],
				[
					-6,
					64
				],
				[
					-6,
					70
				],
				[
					-6,
					72
				],
				[
					-6,
					72
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 935888974,
			"isDeleted": false,
			"id": "vog1dLmOPxFb9OV55cViJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 167.44624819624755,
			"y": 3858.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226,
			"height": 189,
			"seed": 638347538,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					1
				],
				[
					1,
					5
				],
				[
					20,
					19
				],
				[
					62,
					44
				],
				[
					114,
					76
				],
				[
					160,
					110
				],
				[
					208,
					139
				],
				[
					215,
					143
				],
				[
					211,
					144
				],
				[
					186,
					148
				],
				[
					145,
					162
				],
				[
					95,
					168
				],
				[
					51,
					174
				],
				[
					30,
					177
				],
				[
					26,
					178
				],
				[
					26,
					179
				],
				[
					26,
					181
				],
				[
					21,
					185
				],
				[
					16,
					187
				],
				[
					13,
					188
				],
				[
					12,
					189
				],
				[
					11,
					187
				],
				[
					11,
					184
				],
				[
					11,
					179
				],
				[
					10,
					153
				],
				[
					10,
					127
				],
				[
					10,
					102
				],
				[
					5,
					83
				],
				[
					1,
					67
				],
				[
					0,
					61
				],
				[
					-3,
					52
				],
				[
					-6,
					42
				],
				[
					-9,
					30
				],
				[
					-10,
					24
				],
				[
					-11,
					19
				],
				[
					-11,
					18
				],
				[
					-11,
					16
				],
				[
					-11,
					14
				],
				[
					-11,
					10
				],
				[
					-11,
					5
				],
				[
					-11,
					2
				],
				[
					-11,
					0
				],
				[
					-11,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 147,
			"versionNonce": 1830644626,
			"isDeleted": false,
			"id": "wBqIYkXKt7BKB4udjJDiO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 146.44624819624755,
			"y": 3912.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206,
			"height": 5,
			"seed": 1578625294,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-45,
					0
				],
				[
					-105,
					-2
				],
				[
					-163,
					-2
				],
				[
					-200,
					-2
				],
				[
					-205,
					-4
				],
				[
					-205,
					-4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 171,
			"versionNonce": 242110094,
			"isDeleted": false,
			"id": "k1w7yvflY4e8iZe3DcHM4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 174.44624819624755,
			"y": 4003.2003968253975,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 189,
			"height": 126,
			"seed": 1174371726,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8,
					1
				],
				[
					-21,
					1
				],
				[
					-65,
					5
				],
				[
					-107,
					11
				],
				[
					-142,
					14
				],
				[
					-174,
					14
				],
				[
					-184,
					14
				],
				[
					-186,
					14
				],
				[
					-187,
					14
				],
				[
					-188,
					15
				],
				[
					-188,
					29
				],
				[
					-184,
					42
				],
				[
					-182,
					56
				],
				[
					-181,
					67
				],
				[
					-181,
					77
				],
				[
					-181,
					84
				],
				[
					-181,
					93
				],
				[
					-181,
					99
				],
				[
					-181,
					104
				],
				[
					-180,
					107
				],
				[
					-180,
					108
				],
				[
					-180,
					108
				],
				[
					-180,
					109
				],
				[
					-180,
					110
				],
				[
					-180,
					112
				],
				[
					-180,
					114
				],
				[
					-180,
					116
				],
				[
					-180,
					118
				],
				[
					-180,
					122
				],
				[
					-180,
					123
				],
				[
					-180,
					124
				],
				[
					-181,
					126
				],
				[
					-182,
					126
				],
				[
					-182,
					126
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 145,
			"versionNonce": 290335058,
			"isDeleted": false,
			"id": "hm_PsM0p9FCIylIQ2zBjn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 13.446248196247552,
			"y": 4126.200396825398,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 7,
			"seed": 971729490,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					-1
				],
				[
					-2,
					-2
				],
				[
					-13,
					-2
				],
				[
					-27,
					-2
				],
				[
					-45,
					2
				],
				[
					-56,
					5
				],
				[
					-60,
					5
				],
				[
					-61,
					5
				],
				[
					-61,
					5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 140,
			"versionNonce": 285297870,
			"isDeleted": false,
			"id": "_h0utdyah2B7WV8xLeblO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -7.553751803752448,
			"y": 4145.200396825398,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 4,
			"seed": 1016372174,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					0
				],
				[
					-8,
					2
				],
				[
					-11,
					4
				],
				[
					-11,
					4
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 143,
			"versionNonce": 1948331794,
			"isDeleted": false,
			"id": "_53rWmlSqCuCxVu1JlMjN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5.446248196247552,
			"y": 4166.200396825398,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 1,
			"seed": 2037272594,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1,
					0
				],
				[
					-1,
					0
				],
				[
					-3,
					0
				],
				[
					-7,
					0
				],
				[
					-8,
					0
				],
				[
					-9,
					1
				],
				[
					-9,
					1
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 125,
			"versionNonce": 1025147662,
			"isDeleted": false,
			"id": "Na7t5ieL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 193.44624819624755,
			"y": 3997.2003968253975,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 25,
			"seed": 1466692110,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 437091538,
			"isDeleted": false,
			"id": "NCqUJGAH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 187.44624819624755,
			"y": 3903.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 25,
			"seed": 453934546,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-",
			"rawText": "-",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 138,
			"versionNonce": 1966272846,
			"isDeleted": false,
			"id": "sHUe6PyopSJ_wIn73BqP6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 373.44624819624755,
			"y": 3996.2003968253975,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 1098809422,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 160,
			"versionNonce": 1621758610,
			"isDeleted": false,
			"id": "M5xxRtRCF3OUYj1SasCho",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 370.44624819624755,
			"y": 3995.2003968253975,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 105,
			"height": 1,
			"seed": 2078471058,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					4,
					0
				],
				[
					13,
					0
				],
				[
					37,
					0
				],
				[
					55,
					0
				],
				[
					62,
					0
				],
				[
					63,
					0
				],
				[
					64,
					0
				],
				[
					64,
					0
				],
				[
					66,
					0
				],
				[
					70,
					0
				],
				[
					71,
					0
				],
				[
					72,
					0
				],
				[
					73,
					0
				],
				[
					75,
					0
				],
				[
					78,
					0
				],
				[
					83,
					0
				],
				[
					89,
					0
				],
				[
					93,
					0
				],
				[
					98,
					0
				],
				[
					100,
					0
				],
				[
					103,
					0
				],
				[
					104,
					0
				],
				[
					105,
					0
				],
				[
					105,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 108,
			"versionNonce": 1688442766,
			"isDeleted": false,
			"id": "TkTEChHt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 423.44624819624755,
			"y": 3958.2003968253966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 25,
			"seed": 1587889806,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "v0",
			"rawText": "v0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "line",
			"version": 225,
			"versionNonce": 1521348690,
			"isDeleted": false,
			"id": "ZM8Z7bDU1H7W0NXlG4Hz2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 48.94624819624755,
			"y": 3909.751984126984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127.14285714285717,
			"height": 131.4285714285714,
			"seed": 798573774,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
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
					-1.428571428571388,
					-125.71428571428567
				],
				[
					125.71428571428578,
					-131.4285714285714
				]
			]
		},
		{
			"type": "freedraw",
			"version": 223,
			"versionNonce": 1671787982,
			"isDeleted": false,
			"id": "6lV67w3H2YlGLEoLwQFy9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 173.231962481962,
			"y": 3775.4662698412703,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 194.28571428571422,
			"height": 128.57142857142856,
			"seed": 623163154,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					4.285714285714221,
					-2.8571428571428896
				],
				[
					8.571428571428555,
					-12.85714285714289
				],
				[
					10,
					-14.285714285714334
				],
				[
					11.428571428571445,
					-11.428571428571445
				],
				[
					11.428571428571445,
					-8.571428571428612
				],
				[
					14.28571428571422,
					0
				],
				[
					15.714285714285666,
					5.714285714285666
				],
				[
					17.14285714285711,
					10
				],
				[
					18.571428571428555,
					12.857142857142833
				],
				[
					18.571428571428555,
					14.285714285714278
				],
				[
					17.14285714285711,
					15.714285714285666
				],
				[
					15.714285714285666,
					4.285714285714278
				],
				[
					18.571428571428555,
					-7.142857142857167
				],
				[
					22.85714285714289,
					-15.714285714285722
				],
				[
					25.714285714285666,
					-20
				],
				[
					27.14285714285711,
					-18.571428571428612
				],
				[
					30,
					-11.428571428571445
				],
				[
					32.85714285714289,
					-5.714285714285722
				],
				[
					34.28571428571422,
					-2.8571428571428896
				],
				[
					34.28571428571422,
					-1.4285714285714448
				],
				[
					34.28571428571422,
					0
				],
				[
					35.714285714285666,
					-1.4285714285714448
				],
				[
					38.571428571428555,
					-5.714285714285722
				],
				[
					38.571428571428555,
					-8.571428571428612
				],
				[
					41.428571428571445,
					-15.714285714285722
				],
				[
					41.428571428571445,
					-18.571428571428612
				],
				[
					42.85714285714289,
					-20
				],
				[
					42.85714285714289,
					-17.142857142857167
				],
				[
					42.85714285714289,
					-12.85714285714289
				],
				[
					42.85714285714289,
					-8.571428571428612
				],
				[
					45.714285714285666,
					1.428571428571388
				],
				[
					45.714285714285666,
					4.285714285714278
				],
				[
					47.14285714285711,
					8.571428571428555
				],
				[
					48.571428571428555,
					11.428571428571388
				],
				[
					51.428571428571445,
					10
				],
				[
					52.85714285714289,
					8.571428571428555
				],
				[
					55.714285714285666,
					5.714285714285666
				],
				[
					57.14285714285711,
					5.714285714285666
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					58.571428571428555,
					2.857142857142833
				],
				[
					58.571428571428555,
					0
				],
				[
					58.571428571428555,
					-4.285714285714334
				],
				[
					58.571428571428555,
					-7.142857142857167
				],
				[
					58.571428571428555,
					-10
				],
				[
					60,
					-11.428571428571445
				],
				[
					64.28571428571422,
					-8.571428571428612
				],
				[
					71.42857142857144,
					-8.571428571428612
				],
				[
					78.57142857142856,
					-7.142857142857167
				],
				[
					82.85714285714289,
					-7.142857142857167
				],
				[
					85.71428571428567,
					-7.142857142857167
				],
				[
					87.14285714285711,
					-7.142857142857167
				],
				[
					88.57142857142856,
					-7.142857142857167
				],
				[
					90,
					-7.142857142857167
				],
				[
					90,
					-7.142857142857167
				],
				[
					111.42857142857144,
					-7.142857142857167
				],
				[
					134.28571428571422,
					-7.142857142857167
				],
				[
					141.42857142857144,
					-7.142857142857167
				],
				[
					145.71428571428567,
					-7.142857142857167
				],
				[
					147.1428571428571,
					-5.714285714285722
				],
				[
					145.71428571428567,
					-1.4285714285714448
				],
				[
					142.8571428571429,
					8.571428571428555
				],
				[
					142.8571428571429,
					18.571428571428555
				],
				[
					142.8571428571429,
					27.14285714285711
				],
				[
					142.8571428571429,
					30
				],
				[
					144.28571428571422,
					32.85714285714283
				],
				[
					145.71428571428567,
					32.85714285714283
				],
				[
					145.71428571428567,
					32.85714285714283
				],
				[
					152.8571428571429,
					32.85714285714283
				],
				[
					160,
					32.85714285714283
				],
				[
					161.42857142857144,
					32.85714285714283
				],
				[
					161.42857142857144,
					32.85714285714283
				],
				[
					162.8571428571429,
					34.28571428571428
				],
				[
					161.42857142857144,
					37.14285714285711
				],
				[
					154.28571428571422,
					41.42857142857139
				],
				[
					147.1428571428571,
					45.714285714285666
				],
				[
					140,
					50
				],
				[
					135.71428571428567,
					51.428571428571445
				],
				[
					137.1428571428571,
					52.85714285714289
				],
				[
					138.57142857142856,
					54.285714285714334
				],
				[
					144.28571428571422,
					55.714285714285666
				],
				[
					151.42857142857144,
					55.714285714285666
				],
				[
					155.71428571428567,
					55.714285714285666
				],
				[
					158.57142857142856,
					55.714285714285666
				],
				[
					158.57142857142856,
					55.714285714285666
				],
				[
					151.42857142857144,
					58.571428571428555
				],
				[
					142.8571428571429,
					61.428571428571445
				],
				[
					135.71428571428567,
					64.28571428571433
				],
				[
					138.57142857142856,
					65.71428571428567
				],
				[
					147.1428571428571,
					65.71428571428567
				],
				[
					154.28571428571422,
					68.57142857142856
				],
				[
					160,
					70
				],
				[
					162.8571428571429,
					70
				],
				[
					164.28571428571422,
					71.42857142857144
				],
				[
					164.28571428571422,
					71.42857142857144
				],
				[
					164.28571428571422,
					72.85714285714289
				],
				[
					164.28571428571422,
					77.14285714285711
				],
				[
					165.71428571428567,
					84.28571428571422
				],
				[
					165.71428571428567,
					87.14285714285711
				],
				[
					167.1428571428571,
					92.85714285714289
				],
				[
					167.1428571428571,
					95.71428571428567
				],
				[
					167.1428571428571,
					98.57142857142856
				],
				[
					167.1428571428571,
					101.42857142857144
				],
				[
					168.57142857142856,
					104.28571428571422
				],
				[
					167.1428571428571,
					107.14285714285711
				],
				[
					168.57142857142856,
					107.14285714285711
				],
				[
					172.8571428571429,
					104.28571428571422
				],
				[
					188.57142857142856,
					102.85714285714289
				],
				[
					192.8571428571429,
					101.42857142857144
				],
				[
					194.28571428571422,
					101.42857142857144
				],
				[
					190,
					102.85714285714289
				],
				[
					182.8571428571429,
					104.28571428571422
				],
				[
					178.57142857142856,
					105.71428571428567
				],
				[
					174.28571428571422,
					105.71428571428567
				],
				[
					168.57142857142856,
					107.14285714285711
				],
				[
					167.1428571428571,
					107.14285714285711
				],
				[
					165.71428571428567,
					107.14285714285711
				],
				[
					164.28571428571422,
					107.14285714285711
				],
				[
					157.1428571428571,
					107.14285714285711
				],
				[
					152.8571428571429,
					107.14285714285711
				],
				[
					151.42857142857144,
					107.14285714285711
				],
				[
					150,
					108.57142857142856
				],
				[
					150,
					108.57142857142856
				],
				[
					150,
					108.57142857142856
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 118,
			"versionNonce": 737154578,
			"isDeleted": false,
			"id": "XaSYg5aTWxr7hCz8ZbLks",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 353.231962481962,
			"y": 3889.751984126984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.428571428571445,
			"height": 4.285714285714334,
			"seed": 905149198,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					1.4285714285714448
				],
				[
					-1.4285714285714448,
					2.8571428571428896
				],
				[
					-2.8571428571428896,
					2.8571428571428896
				],
				[
					-5.714285714285779,
					2.8571428571428896
				],
				[
					-10,
					2.8571428571428896
				],
				[
					-17.14285714285711,
					2.8571428571428896
				],
				[
					-18.571428571428555,
					2.8571428571428896
				],
				[
					-21.428571428571445,
					4.285714285714334
				],
				[
					-21.428571428571445,
					4.285714285714334
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 111,
			"versionNonce": 1532070926,
			"isDeleted": false,
			"id": "LAl1-n9T8baW7ERLCO8Er",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.80339105339044,
			"y": 3899.751984126984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 1902118098,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 229,
			"versionNonce": 1701282770,
			"isDeleted": false,
			"id": "ANLfU26Ltn6qmgcshoUnV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 311.80339105339044,
			"y": 3768.3234126984125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 232.8571428571429,
			"height": 240,
			"seed": 1479338318,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					2.8571428571428896,
					0
				],
				[
					7.14285714285711,
					0
				],
				[
					12.85714285714289,
					0
				],
				[
					20,
					1.4285714285714448
				],
				[
					25.714285714285666,
					2.857142857142833
				],
				[
					31.428571428571445,
					2.857142857142833
				],
				[
					37.14285714285711,
					4.285714285714278
				],
				[
					41.428571428571445,
					4.285714285714278
				],
				[
					44.285714285714334,
					5.714285714285722
				],
				[
					45.714285714285666,
					5.714285714285722
				],
				[
					47.14285714285711,
					7.142857142857167
				],
				[
					48.571428571428555,
					7.142857142857167
				],
				[
					50,
					7.142857142857167
				],
				[
					52.85714285714289,
					7.142857142857167
				],
				[
					54.285714285714334,
					7.142857142857167
				],
				[
					54.285714285714334,
					7.142857142857167
				],
				[
					55.714285714285666,
					7.142857142857167
				],
				[
					58.571428571428555,
					4.285714285714278
				],
				[
					60,
					2.857142857142833
				],
				[
					62.85714285714289,
					5.714285714285722
				],
				[
					67.14285714285711,
					11.428571428571445
				],
				[
					70,
					17.142857142857167
				],
				[
					74.28571428571433,
					24.285714285714278
				],
				[
					75.71428571428567,
					27.142857142857167
				],
				[
					80,
					22.857142857142833
				],
				[
					82.85714285714289,
					14.285714285714278
				],
				[
					82.85714285714289,
					8.571428571428555
				],
				[
					82.85714285714289,
					7.142857142857167
				],
				[
					82.85714285714289,
					5.714285714285722
				],
				[
					84.28571428571433,
					4.285714285714278
				],
				[
					87.14285714285711,
					7.142857142857167
				],
				[
					88.57142857142856,
					8.571428571428555
				],
				[
					90,
					10
				],
				[
					90,
					11.428571428571445
				],
				[
					90,
					11.428571428571445
				],
				[
					92.85714285714289,
					10
				],
				[
					95.71428571428567,
					7.142857142857167
				],
				[
					98.57142857142856,
					0
				],
				[
					100,
					-5.714285714285722
				],
				[
					100,
					-12.857142857142833
				],
				[
					101.42857142857144,
					-8.571428571428555
				],
				[
					101.42857142857144,
					-2.857142857142833
				],
				[
					102.85714285714289,
					0
				],
				[
					102.85714285714289,
					1.4285714285714448
				],
				[
					102.85714285714289,
					5.714285714285722
				],
				[
					102.85714285714289,
					7.142857142857167
				],
				[
					102.85714285714289,
					10
				],
				[
					102.85714285714289,
					12.857142857142833
				],
				[
					104.28571428571433,
					14.285714285714278
				],
				[
					105.71428571428567,
					15.714285714285722
				],
				[
					108.57142857142856,
					15.714285714285722
				],
				[
					115.71428571428567,
					15.714285714285722
				],
				[
					125.71428571428567,
					15.714285714285722
				],
				[
					134.28571428571433,
					15.714285714285722
				],
				[
					137.1428571428571,
					15.714285714285722
				],
				[
					138.57142857142856,
					15.714285714285722
				],
				[
					140,
					15.714285714285722
				],
				[
					144.28571428571433,
					15.714285714285722
				],
				[
					147.1428571428571,
					15.714285714285722
				],
				[
					151.42857142857144,
					15.714285714285722
				],
				[
					152.8571428571429,
					15.714285714285722
				],
				[
					154.28571428571433,
					17.142857142857167
				],
				[
					154.28571428571433,
					21.428571428571445
				],
				[
					154.28571428571433,
					27.142857142857167
				],
				[
					154.28571428571433,
					34.28571428571428
				],
				[
					154.28571428571433,
					40
				],
				[
					154.28571428571433,
					44.28571428571428
				],
				[
					154.28571428571433,
					47.14285714285717
				],
				[
					154.28571428571433,
					51.428571428571445
				],
				[
					155.71428571428567,
					55.71428571428572
				],
				[
					157.1428571428571,
					60.00000000000006
				],
				[
					157.1428571428571,
					65.71428571428572
				],
				[
					157.1428571428571,
					70.00000000000006
				],
				[
					157.1428571428571,
					74.28571428571428
				],
				[
					158.57142857142856,
					80.00000000000006
				],
				[
					158.57142857142856,
					82.85714285714283
				],
				[
					158.57142857142856,
					88.57142857142861
				],
				[
					160,
					92.85714285714283
				],
				[
					160,
					95.71428571428572
				],
				[
					161.42857142857144,
					97.14285714285717
				],
				[
					161.42857142857144,
					98.57142857142861
				],
				[
					161.42857142857144,
					100.00000000000006
				],
				[
					161.42857142857144,
					102.85714285714283
				],
				[
					161.42857142857144,
					104.28571428571428
				],
				[
					161.42857142857144,
					108.57142857142861
				],
				[
					161.42857142857144,
					111.42857142857139
				],
				[
					161.42857142857144,
					118.57142857142861
				],
				[
					161.42857142857144,
					122.85714285714283
				],
				[
					161.42857142857144,
					127.14285714285717
				],
				[
					161.42857142857144,
					130.00000000000006
				],
				[
					161.42857142857144,
					131.4285714285714
				],
				[
					160,
					132.85714285714283
				],
				[
					160,
					134.28571428571428
				],
				[
					160,
					137.14285714285717
				],
				[
					160,
					138.5714285714286
				],
				[
					158.57142857142856,
					140.00000000000006
				],
				[
					158.57142857142856,
					147.14285714285717
				],
				[
					157.1428571428571,
					157.14285714285717
				],
				[
					157.1428571428571,
					168.5714285714286
				],
				[
					157.1428571428571,
					187.14285714285717
				],
				[
					157.1428571428571,
					197.14285714285717
				],
				[
					157.1428571428571,
					204.28571428571428
				],
				[
					155.71428571428567,
					210.00000000000006
				],
				[
					155.71428571428567,
					212.85714285714283
				],
				[
					155.71428571428567,
					214.28571428571428
				],
				[
					154.28571428571433,
					215.71428571428572
				],
				[
					154.28571428571433,
					215.71428571428572
				],
				[
					154.28571428571433,
					217.14285714285717
				],
				[
					154.28571428571433,
					218.5714285714286
				],
				[
					154.28571428571433,
					221.4285714285714
				],
				[
					155.71428571428567,
					222.85714285714283
				],
				[
					157.1428571428571,
					224.28571428571428
				],
				[
					157.1428571428571,
					225.71428571428572
				],
				[
					158.57142857142856,
					227.14285714285717
				],
				[
					160,
					227.14285714285717
				],
				[
					165.71428571428567,
					225.71428571428572
				],
				[
					185.71428571428567,
					221.4285714285714
				],
				[
					194.28571428571433,
					220.00000000000006
				],
				[
					202.8571428571429,
					218.5714285714286
				],
				[
					204.28571428571433,
					218.5714285714286
				],
				[
					205.71428571428567,
					218.5714285714286
				],
				[
					212.8571428571429,
					218.5714285714286
				],
				[
					214.28571428571433,
					218.5714285714286
				],
				[
					217.1428571428571,
					218.5714285714286
				],
				[
					220,
					218.5714285714286
				],
				[
					221.42857142857144,
					218.5714285714286
				],
				[
					222.8571428571429,
					218.5714285714286
				],
				[
					224.28571428571433,
					218.5714285714286
				],
				[
					230,
					217.14285714285717
				],
				[
					232.8571428571429,
					215.71428571428572
				],
				[
					232.8571428571429,
					215.71428571428572
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 81,
			"versionNonce": 698407502,
			"isDeleted": false,
			"id": "0ofMQC33",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 276.0891053391048,
			"y": 3815.037698412698,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 25,
			"seed": 1013684882,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R3",
			"rawText": "R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 1630222738,
			"isDeleted": false,
			"id": "6cFbl7P2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 110.66053391053322,
			"y": 4015.8234126984134,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 25,
			"seed": 1425963090,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i = o",
			"rawText": "i = o",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 69,
			"versionNonce": 90988686,
			"isDeleted": false,
			"id": "Tf9rfx6v",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -128.44660894660956,
			"y": 3542.3333333333335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 406,
			"height": 50,
			"seed": 1935771730,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rp  voltage accross it is zero so byebye\n",
			"rawText": "Rp  voltage accross it is zero so byebye\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 62,
			"versionNonce": 510801746,
			"isDeleted": false,
			"id": "QEVLoGjoM_qQ_aO9M6K6p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -60.44660894660956,
			"y": 3903.3333333333335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 201,
			"height": 50,
			"seed": 1691973582,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-4,
					0
				],
				[
					-20,
					0
				],
				[
					-64,
					0
				],
				[
					-104,
					0
				],
				[
					-124,
					0
				],
				[
					-126,
					0
				],
				[
					-128,
					0
				],
				[
					-136,
					0
				],
				[
					-148,
					0
				],
				[
					-160,
					-4
				],
				[
					-164,
					-4
				],
				[
					-170,
					-4
				],
				[
					-174,
					-4
				],
				[
					-176,
					-4
				],
				[
					-178,
					-4
				],
				[
					-184,
					-4
				],
				[
					-186,
					-4
				],
				[
					-190,
					-4
				],
				[
					-196,
					-6
				],
				[
					-198,
					-6
				],
				[
					-198,
					-6
				],
				[
					-200,
					-6
				],
				[
					-200,
					-2
				],
				[
					-200,
					6
				],
				[
					-200,
					14
				],
				[
					-200,
					22
				],
				[
					-200,
					26
				],
				[
					-200,
					30
				],
				[
					-200,
					34
				],
				[
					-200,
					36
				],
				[
					-200,
					40
				],
				[
					-200,
					42
				],
				[
					-200,
					44
				],
				[
					-200,
					44
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "ellipse",
			"version": 105,
			"versionNonce": 1651318478,
			"isDeleted": false,
			"id": "2OdQ6HOWghLpy1bXHDDDR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -303.5894660894667,
			"y": 3943.4761904761895,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 74.28571428571433,
			"height": 95.71428571428578,
			"seed": 465360018,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 48,
			"versionNonce": 496205074,
			"isDeleted": false,
			"id": "_46eunJD7Y2lSOesMn7jN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -269.8751803751809,
			"y": 4037.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.285714285714221,
			"height": 95.71428571428532,
			"seed": 1850476174,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					0,
					2.857142857143117
				],
				[
					0,
					11.428571428571558
				],
				[
					-1.4285714285713311,
					24.28571428571422
				],
				[
					-2.857142857142776,
					37.14285714285734
				],
				[
					-4.285714285714221,
					47.14285714285734
				],
				[
					-4.285714285714221,
					54.28571428571422
				],
				[
					-4.285714285714221,
					58.57142857142844
				],
				[
					-4.285714285714221,
					60
				],
				[
					-4.285714285714221,
					61.42857142857156
				],
				[
					-4.285714285714221,
					62.85714285714312
				],
				[
					-4.285714285714221,
					64.28571428571468
				],
				[
					-4.285714285714221,
					65.71428571428532
				],
				[
					-2.857142857142776,
					67.14285714285688
				],
				[
					-2.857142857142776,
					72.85714285714312
				],
				[
					-1.4285714285713311,
					75.71428571428532
				],
				[
					-1.4285714285713311,
					78.57142857142844
				],
				[
					-1.4285714285713311,
					84.28571428571468
				],
				[
					-1.4285714285713311,
					88.57142857142844
				],
				[
					-1.4285714285713311,
					92.85714285714312
				],
				[
					0,
					95.71428571428532
				],
				[
					0,
					95.71428571428532
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 34,
			"versionNonce": 1430000910,
			"isDeleted": false,
			"id": "FtpXuwf_qI4CY2UIQWYBd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.1608946608951,
			"y": 4139.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 111.42857142857144,
			"height": 2.4285714285715585,
			"seed": 722624910,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.4285714285714448,
					-1.4285714285715585
				],
				[
					-2.8571428571428896,
					-1.4285714285715585
				],
				[
					-32.85714285714289,
					-1.4285714285715585
				],
				[
					-68.57142857142856,
					-1.4285714285715585
				],
				[
					-95.71428571428578,
					-1.4285714285715585
				],
				[
					-108.57142857142856,
					-1.4285714285715585
				],
				[
					-110,
					-1.4285714285715585
				],
				[
					-110,
					-1.4285714285715585
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 31,
			"versionNonce": 1007028946,
			"isDeleted": false,
			"id": "PAJFmK5o2W2ByItFwqAgW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -265.58946608946655,
			"y": 4159.904761904762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.14285714285711,
			"height": 1.4285714285715585,
			"seed": 408791246,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2.8571428571428896,
					1.4285714285715585
				],
				[
					-14.285714285714334,
					1.4285714285715585
				],
				[
					-25.714285714285666,
					1.4285714285715585
				],
				[
					-27.14285714285711,
					1.4285714285715585
				],
				[
					-27.14285714285711,
					1.4285714285715585
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 30,
			"versionNonce": 2001879886,
			"isDeleted": false,
			"id": "-q7izzF6JbDb5U402RJuE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -274.1608946608951,
			"y": 4181.333333333334,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.8571428571428896,
			"height": 1,
			"seed": 299881554,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.4285714285714448,
					0
				],
				[
					-2.8571428571428896,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 112,
			"versionNonce": 274784402,
			"isDeleted": false,
			"id": "7gBuMiM4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480.018037518038,
			"y": 3965.976190476191,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 146,
			"height": 25,
			"seed": 1436613134,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Current source",
			"rawText": "Current source",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 1258858894,
			"isDeleted": false,
			"id": "sPBpD4G2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 375.8391053391049,
			"y": 3708.0476190476193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 103,
			"height": 25,
			"seed": 73155406,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rl (r load)",
			"rawText": "Rl (r load)",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 1180368466,
			"isDeleted": false,
			"id": "XYuFKL85",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 184.41053391053356,
			"y": 3706.6190476190477,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 25,
			"seed": 1362311438,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R2",
			"rawText": "R2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 530073550,
			"isDeleted": false,
			"id": "oDhQf5A6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 387.26767676767645,
			"y": 3812.3333333333335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25,
			"height": 25,
			"seed": 1838022674,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [
				"4j1r09u1qb0SgaFGAW8ei"
			],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "I0",
			"rawText": "I0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 2060149778,
			"isDeleted": false,
			"id": "h8m97BRR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1.5533910533906692,
			"y": 3803.761904761905,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25,
			"height": 25,
			"seed": 562992334,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "I2",
			"rawText": "I2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "arrow",
			"version": 73,
			"versionNonce": 1964645902,
			"isDeleted": false,
			"id": "Qat5WGlpjQnR8Zh9LCgE-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 20.12481962481911,
			"y": 3881.333333333334,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.8571428571426623,
			"height": 34.285714285714675,
			"seed": 103196686,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-2.8571428571426623,
					-34.285714285714675
				]
			]
		},
		{
			"type": "arrow",
			"version": 63,
			"versionNonce": 396956114,
			"isDeleted": false,
			"id": "1V-guEwD6EmveqILgd8Fc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -272.7323232323238,
			"y": 4021.333333333334,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.285714285714221,
			"height": 52.85714285714312,
			"seed": 2017978126,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					4.285714285714221,
					-52.85714285714312
				]
			]
		},
		{
			"type": "arrow",
			"version": 73,
			"versionNonce": 1619471438,
			"isDeleted": false,
			"id": "4j1r09u1qb0SgaFGAW8ei",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 378.6962481962478,
			"y": 3798.476190476191,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62.857142857142776,
			"height": 1.4285714285711038,
			"seed": 1762013586,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": {
				"elementId": "VH0RjkPrae39516_nh_Ke",
				"focus": -2.0991746031745904,
				"gap": 13.857142857142662
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					62.857142857142776,
					-1.4285714285711038
				]
			]
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 806029202,
			"isDeleted": false,
			"id": "ENCbwCQi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -131.30375180375245,
			"y": 3940.9047619047633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 25,
			"seed": 219599762,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Is",
			"rawText": "Is",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "arrow",
			"version": 66,
			"versionNonce": 1874358926,
			"isDeleted": false,
			"id": "JJudsC7jK76sx9G1Ccfxg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -168.44660894660967,
			"y": 3924.1904761904775,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 114.28571428571433,
			"height": 5.714285714285779,
			"seed": 1785043726,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					114.28571428571433,
					5.714285714285779
				]
			]
		},
		{
			"type": "text",
			"version": 69,
			"versionNonce": 1546143058,
			"isDeleted": false,
			"id": "pSAFUA6q",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -337.0180375180382,
			"y": 4503.7619047619055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 530,
			"height": 75,
			"seed": 1215058190,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 60.000000000000014,
			"fontFamily": 1,
			"text": "I0 = Is(1+R2/R3)",
			"rawText": "I0 = Is(1+R2/R3)",
			"baseline": 53,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 224850126,
			"isDeleted": false,
			"id": "FCrx52qD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -355.58946608946667,
			"y": 4403.761904761906,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 232,
			"height": 38,
			"seed": 1099810514,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 30.28571428571428,
			"fontFamily": 1,
			"text": "Gain on current",
			"rawText": "Gain on current",
			"baseline": 27,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 358075154,
			"isDeleted": false,
			"id": "wfPgmAsc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 9.93434343434302,
			"y": 3025.0952380952385,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 284,
			"height": 25,
			"seed": 776943954,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Current source with a opamp",
			"rawText": "Current source with a opamp",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "rectangle",
			"version": 83,
			"versionNonce": 1697359630,
			"isDeleted": false,
			"id": "HxhZuVp1CMiGguum599Kg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -490.06565656565704,
			"y": 3017.428571428572,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 1516.666666666667,
			"height": 1673.3333333333335,
			"seed": 963845202,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 303077586,
			"isDeleted": false,
			"id": "0e-3fzo_94uqgu5rkvk-U",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.39898989899038,
			"y": 4900.761904761906,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 1270609554,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 1199543630,
			"isDeleted": false,
			"id": "FOi9uu4M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -443.3989898989906,
			"y": 4841.761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1682,
			"height": 262,
			"seed": 216035026,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 208.0000000000001,
			"fontFamily": 1,
			"text": "Summing amplifier",
			"rawText": "Summing amplifier",
			"baseline": 184,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 568962706,
			"isDeleted": false,
			"id": "UuUiWQr4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -358.3989898989905,
			"y": 5205.09523809524,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 190,
			"height": 37,
			"seed": 694373134,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 29.33333333333358,
			"fontFamily": 1,
			"text": "How to build ",
			"rawText": "How to build ",
			"baseline": 26,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 138,
			"versionNonce": 230407054,
			"isDeleted": false,
			"id": "E4QyXKnnmbZFl9HXdVABr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 175.767676767676,
			"y": 5715.761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 745,
			"height": 322.66666666666606,
			"seed": 746084306,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					6.666666666666686,
					0
				],
				[
					43.333333333333314,
					-5
				],
				[
					88.33333333333337,
					-6.66666666666606
				],
				[
					148.33333333333337,
					-6.66666666666606
				],
				[
					193.33333333333337,
					-6.66666666666606
				],
				[
					215,
					-5
				],
				[
					221.66666666666669,
					-3.33333333333303
				],
				[
					223.33333333333334,
					-5
				],
				[
					223.33333333333334,
					-8.33333333333303
				],
				[
					223.33333333333334,
					-10
				],
				[
					223.33333333333334,
					-11.66666666666606
				],
				[
					225,
					-15
				],
				[
					225,
					-16.66666666666606
				],
				[
					225,
					-23.33333333333303
				],
				[
					225,
					-38.33333333333303
				],
				[
					225,
					-53.33333333333303
				],
				[
					225,
					-71.66666666666606
				],
				[
					225,
					-91.66666666666606
				],
				[
					225,
					-111.66666666666606
				],
				[
					225,
					-130
				],
				[
					225,
					-148.33333333333303
				],
				[
					225,
					-158.33333333333303
				],
				[
					225,
					-165
				],
				[
					226.66666666666669,
					-171.66666666666606
				],
				[
					226.66666666666669,
					-183.33333333333303
				],
				[
					226.66666666666669,
					-198.33333333333303
				],
				[
					230,
					-210
				],
				[
					231.66666666666669,
					-221.66666666666606
				],
				[
					231.66666666666669,
					-223.33333333333303
				],
				[
					231.66666666666669,
					-225
				],
				[
					231.66666666666669,
					-231.66666666666606
				],
				[
					231.66666666666669,
					-238.33333333333303
				],
				[
					231.66666666666669,
					-243.33333333333303
				],
				[
					230,
					-251.66666666666606
				],
				[
					230,
					-258.33333333333303
				],
				[
					230,
					-261.66666666666606
				],
				[
					230,
					-265
				],
				[
					230,
					-270
				],
				[
					230,
					-271.66666666666606
				],
				[
					230,
					-273.33333333333303
				],
				[
					233.33333333333334,
					-275
				],
				[
					250,
					-273.33333333333303
				],
				[
					298.33333333333337,
					-273.33333333333303
				],
				[
					348.33333333333337,
					-273.33333333333303
				],
				[
					385,
					-273.33333333333303
				],
				[
					386.6666666666667,
					-273.33333333333303
				],
				[
					388.33333333333337,
					-273.33333333333303
				],
				[
					391.6666666666667,
					-275
				],
				[
					398.33333333333337,
					-298.33333333333303
				],
				[
					403.33333333333337,
					-305
				],
				[
					405,
					-306.66666666666606
				],
				[
					406.6666666666667,
					-308.33333333333303
				],
				[
					408.33333333333337,
					-303.33333333333303
				],
				[
					413.33333333333337,
					-290
				],
				[
					416.6666666666667,
					-276.66666666666606
				],
				[
					423.33333333333337,
					-256.66666666666606
				],
				[
					425,
					-255
				],
				[
					426.6666666666667,
					-258.33333333333303
				],
				[
					428.33333333333337,
					-263.33333333333303
				],
				[
					435,
					-276.66666666666606
				],
				[
					440,
					-288.33333333333303
				],
				[
					443.33333333333337,
					-291.66666666666606
				],
				[
					446.6666666666667,
					-291.66666666666606
				],
				[
					451.6666666666667,
					-276.66666666666606
				],
				[
					456.6666666666667,
					-268.33333333333303
				],
				[
					458.33333333333337,
					-265
				],
				[
					463.33333333333337,
					-270
				],
				[
					468.33333333333337,
					-275
				],
				[
					480,
					-291.66666666666606
				],
				[
					498.33333333333337,
					-311.66666666666606
				],
				[
					510,
					-321.66666666666606
				],
				[
					513.3333333333334,
					-318.33333333333303
				],
				[
					516.6666666666667,
					-315
				],
				[
					516.6666666666667,
					-311.66666666666606
				],
				[
					518.3333333333334,
					-306.66666666666606
				],
				[
					520,
					-300
				],
				[
					521.6666666666667,
					-296.66666666666606
				],
				[
					530,
					-295
				],
				[
					550,
					-295
				],
				[
					606.6666666666667,
					-295
				],
				[
					641.6666666666667,
					-295
				],
				[
					735,
					-295
				],
				[
					743.3333333333334,
					-295
				],
				[
					745,
					-295
				],
				[
					745,
					-295
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 73,
			"versionNonce": 161090642,
			"isDeleted": false,
			"id": "8ksHxR1GWKAvfhE7uCdFs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 395.767676767676,
			"y": 5707.428571428574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 146.66666666666669,
			"height": 16.66666666666697,
			"seed": 2058869518,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					3.333333333333343,
					0
				],
				[
					10,
					0
				],
				[
					36.666666666666686,
					6.66666666666697
				],
				[
					61.666666666666686,
					10
				],
				[
					75,
					11.66666666666697
				],
				[
					81.66666666666669,
					11.66666666666697
				],
				[
					86.66666666666669,
					11.66666666666697
				],
				[
					91.66666666666669,
					10
				],
				[
					93.33333333333337,
					10
				],
				[
					96.66666666666669,
					8.33333333333303
				],
				[
					101.66666666666669,
					8.33333333333303
				],
				[
					105,
					8.33333333333303
				],
				[
					106.66666666666669,
					6.66666666666697
				],
				[
					108.33333333333337,
					5
				],
				[
					116.66666666666669,
					3.33333333333303
				],
				[
					130,
					0
				],
				[
					138.33333333333337,
					-1.6666666666669698
				],
				[
					145,
					-3.33333333333303
				],
				[
					146.66666666666669,
					-5
				],
				[
					146.66666666666669,
					-5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 67,
			"versionNonce": 2115574222,
			"isDeleted": false,
			"id": "CIe9BQzpuMfffyqqZxJoD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 535.767676767676,
			"y": 5610.761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.666666666666629,
			"height": 291.66666666666697,
			"seed": 356294606,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					3.3333333333339397
				],
				[
					0,
					11.66666666666697
				],
				[
					3.3333333333333712,
					25
				],
				[
					5,
					58.33333333333394
				],
				[
					5,
					103.33333333333394
				],
				[
					5,
					146.66666666666697
				],
				[
					-3.3333333333333144,
					223.33333333333394
				],
				[
					-6.666666666666629,
					250
				],
				[
					-6.666666666666629,
					268.33333333333394
				],
				[
					-3.3333333333333144,
					281.66666666666697
				],
				[
					1.6666666666666856,
					290
				],
				[
					1.6666666666666856,
					291.66666666666697
				],
				[
					0,
					290
				],
				[
					0,
					290
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 90,
			"versionNonce": 1593356818,
			"isDeleted": false,
			"id": "coh9jH5OxRvQE27d0vMX3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 525.767676767676,
			"y": 5605.761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 411.66666666666674,
			"height": 176.66666666666697,
			"seed": 1206219214,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.6666666666666856,
					1.6666666666669698
				],
				[
					3.3333333333333712,
					1.6666666666669698
				],
				[
					10,
					5
				],
				[
					16.666666666666686,
					8.33333333333394
				],
				[
					26.666666666666686,
					13.33333333333394
				],
				[
					38.33333333333337,
					21.66666666666697
				],
				[
					51.666666666666686,
					30
				],
				[
					83.33333333333337,
					45
				],
				[
					116.66666666666669,
					55
				],
				[
					145,
					65
				],
				[
					176.66666666666669,
					75
				],
				[
					193.33333333333337,
					81.66666666666697
				],
				[
					208.33333333333337,
					88.33333333333394
				],
				[
					215,
					93.33333333333394
				],
				[
					221.66666666666674,
					96.66666666666697
				],
				[
					230,
					100
				],
				[
					243.33333333333337,
					103.33333333333394
				],
				[
					253.33333333333337,
					106.66666666666697
				],
				[
					260,
					110
				],
				[
					263.33333333333337,
					113.33333333333394
				],
				[
					273.33333333333337,
					123.33333333333394
				],
				[
					288.33333333333337,
					131.66666666666697
				],
				[
					300,
					135
				],
				[
					315,
					140
				],
				[
					320,
					141.66666666666697
				],
				[
					323.33333333333337,
					143.33333333333394
				],
				[
					330,
					148.33333333333394
				],
				[
					343.33333333333337,
					153.33333333333394
				],
				[
					371.66666666666674,
					160
				],
				[
					393.33333333333337,
					166.66666666666697
				],
				[
					396.66666666666674,
					168.33333333333394
				],
				[
					400,
					170
				],
				[
					403.33333333333337,
					171.66666666666697
				],
				[
					406.66666666666674,
					173.33333333333394
				],
				[
					410,
					175
				],
				[
					411.66666666666674,
					176.66666666666697
				],
				[
					411.66666666666674,
					176.66666666666697
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 94,
			"versionNonce": 800108558,
			"isDeleted": false,
			"id": "JKEZ1unUhx3-q5Ocz2YGy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 532.4343434343427,
			"y": 5897.428571428574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 403.3333333333333,
			"height": 117.66666666666697,
			"seed": 979146578,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					5,
					0
				],
				[
					46.666666666666686,
					-8.33333333333303
				],
				[
					98.33333333333331,
					-25
				],
				[
					143.33333333333331,
					-33.33333333333303
				],
				[
					178.33333333333331,
					-43.33333333333303
				],
				[
					191.66666666666669,
					-46.66666666666697
				],
				[
					201.66666666666669,
					-53.33333333333303
				],
				[
					210.00000000000006,
					-58.33333333333303
				],
				[
					223.33333333333331,
					-65
				],
				[
					236.66666666666669,
					-70
				],
				[
					245.00000000000006,
					-75
				],
				[
					251.66666666666669,
					-78.33333333333303
				],
				[
					266.6666666666667,
					-88.33333333333303
				],
				[
					278.3333333333333,
					-91.66666666666697
				],
				[
					286.6666666666667,
					-96.66666666666697
				],
				[
					295.00000000000006,
					-100
				],
				[
					298.3333333333333,
					-101.66666666666697
				],
				[
					300.00000000000006,
					-101.66666666666697
				],
				[
					303.3333333333333,
					-101.66666666666697
				],
				[
					306.6666666666667,
					-101.66666666666697
				],
				[
					311.6666666666667,
					-101.66666666666697
				],
				[
					316.6666666666667,
					-101.66666666666697
				],
				[
					321.6666666666667,
					-101.66666666666697
				],
				[
					326.6666666666667,
					-103.33333333333303
				],
				[
					330.00000000000006,
					-105
				],
				[
					336.6666666666667,
					-106.66666666666697
				],
				[
					341.6666666666667,
					-108.33333333333303
				],
				[
					343.3333333333333,
					-108.33333333333303
				],
				[
					348.3333333333333,
					-110
				],
				[
					358.3333333333333,
					-111.66666666666697
				],
				[
					363.3333333333333,
					-113.33333333333303
				],
				[
					366.6666666666667,
					-113.33333333333303
				],
				[
					373.3333333333333,
					-113.33333333333303
				],
				[
					378.3333333333333,
					-115
				],
				[
					381.6666666666667,
					-115
				],
				[
					393.3333333333333,
					-116.66666666666697
				],
				[
					396.6666666666667,
					-116.66666666666697
				],
				[
					400.00000000000006,
					-116.66666666666697
				],
				[
					401.6666666666667,
					-116.66666666666697
				],
				[
					403.3333333333333,
					-116.66666666666697
				],
				[
					403.3333333333333,
					-116.66666666666697
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 59,
			"versionNonce": 1694277586,
			"isDeleted": false,
			"id": "ZPVJpGSaR9zYOAX6zD_mp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 569.1010101010094,
			"y": 5699.095238095241,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.333333333333314,
			"height": 1,
			"seed": 1761403406,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					3.3333333333333144,
					0
				],
				[
					8.333333333333314,
					0
				],
				[
					25,
					0
				],
				[
					35,
					0
				],
				[
					38.333333333333314,
					0
				],
				[
					38.333333333333314,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 67,
			"versionNonce": 1853587022,
			"isDeleted": false,
			"id": "hoWnsTUPKDox1xrLD4IPw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 524.1010101010093,
			"y": 5845.761904761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 292.6666666666667,
			"height": 16.66666666666606,
			"seed": 1066167054,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8.333333333333314,
					0
				],
				[
					-66.66666666666663,
					3.33333333333303
				],
				[
					-143.33333333333331,
					3.33333333333303
				],
				[
					-210,
					6.66666666666606
				],
				[
					-248.33333333333331,
					11.66666666666606
				],
				[
					-256.66666666666663,
					11.66666666666606
				],
				[
					-260,
					13.33333333333303
				],
				[
					-265,
					15
				],
				[
					-270,
					16.66666666666606
				],
				[
					-280,
					16.66666666666606
				],
				[
					-288.3333333333333,
					16.66666666666606
				],
				[
					-291.6666666666667,
					16.66666666666606
				],
				[
					-291.6666666666667,
					16.66666666666606
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 1740428690,
			"isDeleted": false,
			"id": "8IOS2On8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 565.767676767676,
			"y": 5804.454212454216,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 51,
			"seed": 607871054,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 40.512820512820475,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 36,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 60,
			"versionNonce": 525501582,
			"isDeleted": false,
			"id": "RKqFi0oHh1NGdS4H6E0Y2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 227.43434343434268,
			"y": 5859.095238095241,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.66666666666663,
			"height": 136.66666666666606,
			"seed": 755485134,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.6666666666666288,
					10
				],
				[
					-1.6666666666666856,
					30
				],
				[
					-6.666666666666686,
					60
				],
				[
					-11.666666666666686,
					96.66666666666606
				],
				[
					-13.333333333333371,
					118.33333333333303
				],
				[
					-15,
					121.66666666666606
				],
				[
					-15,
					123.33333333333303
				],
				[
					-16.666666666666686,
					125
				],
				[
					-16.666666666666686,
					126.66666666666606
				],
				[
					-20,
					133.33333333333303
				],
				[
					-20,
					136.66666666666606
				],
				[
					-20,
					136.66666666666606
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 57,
			"versionNonce": 410014546,
			"isDeleted": false,
			"id": "np0OE_nlwMBHTsZvLoYY-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 255.767676767676,
			"y": 6009.095238095241,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 61,
			"height": 2.66666666666697,
			"seed": 1041333646,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-3.3333333333333144,
					-1.6666666666669698
				],
				[
					-10,
					-1.6666666666669698
				],
				[
					-18.333333333333314,
					-1.6666666666669698
				],
				[
					-30,
					-1.6666666666669698
				],
				[
					-46.666666666666686,
					-1.6666666666669698
				],
				[
					-56.666666666666686,
					0
				],
				[
					-58.333333333333314,
					0
				],
				[
					-60,
					0
				],
				[
					-60,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 54,
			"versionNonce": 602849998,
			"isDeleted": false,
			"id": "2pvxm5VXFggkem7ebgmT7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 225.767676767676,
			"y": 6037.428571428574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21,
			"height": 1,
			"seed": 1718794002,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-3.3333333333333144,
					0
				],
				[
					-6.666666666666686,
					0
				],
				[
					-15,
					0
				],
				[
					-18.333333333333314,
					0
				],
				[
					-20,
					0
				],
				[
					-20,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 55,
			"versionNonce": 1768823058,
			"isDeleted": false,
			"id": "uiDIReHR_dAf8hTWj-0EC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 225.767676767676,
			"y": 6052.428571428574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.666666666666686,
			"height": 3.33333333333303,
			"seed": 1161666066,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					1.6666666666669698
				],
				[
					-3.3333333333333144,
					3.33333333333303
				],
				[
					-6.666666666666686,
					3.33333333333303
				],
				[
					-10,
					3.33333333333303
				],
				[
					-11.666666666666686,
					3.33333333333303
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 112,
			"versionNonce": 1055471886,
			"isDeleted": false,
			"id": "EkFiKTvtBLQ3SZFaDbrnp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 177.43434343434257,
			"y": 5715.761904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 502.6666666666667,
			"height": 458.33333333333303,
			"seed": 1009716494,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666856,
					0
				],
				[
					-13.333333333333314,
					0
				],
				[
					-56.666666666666686,
					0
				],
				[
					-104.99999999999994,
					0
				],
				[
					-128.33333333333331,
					0
				],
				[
					-183.33333333333331,
					0
				],
				[
					-196.66666666666669,
					3.3333333333339397
				],
				[
					-200.00000000000006,
					3.3333333333339397
				],
				[
					-201.66666666666669,
					3.3333333333339397
				],
				[
					-203.33333333333331,
					3.3333333333339397
				],
				[
					-211.66666666666669,
					3.3333333333339397
				],
				[
					-230.00000000000006,
					-1.6666666666660603
				],
				[
					-240.00000000000006,
					-1.6666666666660603
				],
				[
					-258.3333333333333,
					-1.6666666666660603
				],
				[
					-271.6666666666667,
					-3.33333333333303
				],
				[
					-275.00000000000006,
					-3.33333333333303
				],
				[
					-276.6666666666667,
					-3.33333333333303
				],
				[
					-278.3333333333333,
					-3.33333333333303
				],
				[
					-283.3333333333333,
					-3.33333333333303
				],
				[
					-293.3333333333333,
					-3.33333333333303
				],
				[
					-303.3333333333333,
					-3.33333333333303
				],
				[
					-310.00000000000006,
					-3.33333333333303
				],
				[
					-315.00000000000006,
					-3.33333333333303
				],
				[
					-316.6666666666667,
					-3.33333333333303
				],
				[
					-318.3333333333333,
					-3.33333333333303
				],
				[
					-320.00000000000006,
					-3.33333333333303
				],
				[
					-320.00000000000006,
					-3.33333333333303
				],
				[
					-321.6666666666667,
					-3.33333333333303
				],
				[
					-321.6666666666667,
					-1.6666666666660603
				],
				[
					-321.6666666666667,
					10
				],
				[
					-321.6666666666667,
					31.66666666666697
				],
				[
					-321.6666666666667,
					95
				],
				[
					-321.6666666666667,
					205
				],
				[
					-321.6666666666667,
					311.66666666666697
				],
				[
					-321.6666666666667,
					366.66666666666697
				],
				[
					-323.3333333333333,
					381.66666666666697
				],
				[
					-325.00000000000006,
					395
				],
				[
					-328.3333333333333,
					411.66666666666697
				],
				[
					-330.00000000000006,
					416.66666666666697
				],
				[
					-330.00000000000006,
					421.66666666666697
				],
				[
					-331.6666666666667,
					426.66666666666697
				],
				[
					-331.6666666666667,
					428.33333333333394
				],
				[
					-331.6666666666667,
					430
				],
				[
					-331.6666666666667,
					430
				],
				[
					-330.00000000000006,
					438.33333333333394
				],
				[
					-330.00000000000006,
					441.66666666666697
				],
				[
					-330.00000000000006,
					443.33333333333394
				],
				[
					-330.00000000000006,
					445
				],
				[
					-330.00000000000006,
					446.66666666666697
				],
				[
					-330.00000000000006,
					448.33333333333394
				],
				[
					-330.00000000000006,
					448.33333333333394
				],
				[
					-330.00000000000006,
					450
				],
				[
					-330.00000000000006,
					450
				],
				[
					-338.3333333333333,
					451.66666666666697
				],
				[
					-355.00000000000006,
					455
				],
				[
					-381.6666666666667,
					455
				],
				[
					-413.3333333333334,
					455
				],
				[
					-448.3333333333334,
					455
				],
				[
					-483.3333333333334,
					455
				],
				[
					-488.3333333333334,
					455
				],
				[
					-495.00000000000006,
					455
				],
				[
					-498.3333333333334,
					455
				],
				[
					-501.6666666666667,
					455
				],
				[
					-501.6666666666667,
					455
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 61,
			"versionNonce": 1781343954,
			"isDeleted": false,
			"id": "E4otmJwCSXwyHGJxx-WYM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -144.23232323232412,
			"y": 5962.428571428576,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 144.33333333333326,
			"height": 9.33333333333394,
			"seed": 1481605966,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-3.3333333333332575,
					0
				],
				[
					-11.666666666666629,
					0
				],
				[
					-20,
					0
				],
				[
					-36.66666666666663,
					-1.6666666666669698
				],
				[
					-58.33333333333326,
					-5
				],
				[
					-76.66666666666663,
					-6.66666666666697
				],
				[
					-86.66666666666663,
					-6.66666666666697
				],
				[
					-101.66666666666663,
					-6.66666666666697
				],
				[
					-113.33333333333326,
					-6.66666666666697
				],
				[
					-130,
					-6.66666666666697
				],
				[
					-141.66666666666663,
					-8.33333333333394
				],
				[
					-143.33333333333326,
					-8.33333333333394
				],
				[
					-143.33333333333326,
					-8.33333333333394
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 70,
			"versionNonce": 2008737614,
			"isDeleted": false,
			"id": "eJIIKoJ0IcZcH2aOWLs4l",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -147.56565656565738,
			"y": 5710.761904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 117.66666666666674,
			"height": 2.66666666666697,
			"seed": 1738496210,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666667425,
					0
				],
				[
					-3.3333333333333712,
					0
				],
				[
					-15,
					0
				],
				[
					-46.66666666666674,
					0
				],
				[
					-66.66666666666674,
					0
				],
				[
					-76.66666666666674,
					0
				],
				[
					-81.66666666666674,
					0
				],
				[
					-83.33333333333337,
					0
				],
				[
					-85,
					0
				],
				[
					-86.66666666666674,
					0
				],
				[
					-90,
					0
				],
				[
					-91.66666666666674,
					0
				],
				[
					-95,
					0
				],
				[
					-98.33333333333337,
					-1.6666666666669698
				],
				[
					-101.66666666666674,
					-1.6666666666669698
				],
				[
					-106.66666666666674,
					-1.6666666666669698
				],
				[
					-110,
					-1.6666666666669698
				],
				[
					-113.33333333333337,
					-1.6666666666669698
				],
				[
					-115,
					-1.6666666666669698
				],
				[
					-115,
					-1.6666666666669698
				],
				[
					-116.66666666666674,
					-1.6666666666669698
				],
				[
					-116.66666666666674,
					-1.6666666666669698
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 91,
			"versionNonce": 591690898,
			"isDeleted": false,
			"id": "HqcxNbS0op_dqaEHUeN6o",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.2323232323241,
			"y": 6167.428571428576,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 18.33333333333394,
			"seed": 684781010,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666288,
					0
				],
				[
					-6.666666666666629,
					0
				],
				[
					-11.666666666666629,
					-5
				],
				[
					-13.333333333333258,
					-6.66666666666697
				],
				[
					-15,
					-8.33333333333394
				],
				[
					-18.333333333333258,
					-5
				],
				[
					-25,
					1.6666666666660603
				],
				[
					-30,
					8.33333333333303
				],
				[
					-31.66666666666663,
					10
				],
				[
					-38.33333333333326,
					5
				],
				[
					-41.66666666666663,
					1.6666666666660603
				],
				[
					-43.33333333333326,
					0
				],
				[
					-45,
					1.6666666666660603
				],
				[
					-46.66666666666663,
					3.33333333333303
				],
				[
					-46.66666666666663,
					5
				],
				[
					-48.33333333333326,
					8.33333333333303
				],
				[
					-50,
					10
				],
				[
					-55,
					8.33333333333303
				],
				[
					-58.33333333333326,
					5
				],
				[
					-60,
					3.33333333333303
				],
				[
					-61.66666666666663,
					1.6666666666660603
				],
				[
					-65,
					1.6666666666660603
				],
				[
					-70,
					3.33333333333303
				],
				[
					-70,
					3.33333333333303
				],
				[
					-73.33333333333326,
					0
				],
				[
					-76.66666666666674,
					-3.3333333333339397
				],
				[
					-78.33333333333326,
					-5
				],
				[
					-83.33333333333326,
					-3.3333333333339397
				],
				[
					-90,
					-1.6666666666669698
				],
				[
					-93.33333333333326,
					0
				],
				[
					-98.33333333333326,
					1.6666666666660603
				],
				[
					-105,
					1.6666666666660603
				],
				[
					-113.33333333333326,
					3.33333333333303
				],
				[
					-121.66666666666674,
					5
				],
				[
					-130,
					5
				],
				[
					-138.33333333333326,
					5
				],
				[
					-143.33333333333326,
					5
				],
				[
					-151.66666666666674,
					5
				],
				[
					-161.66666666666674,
					5
				],
				[
					-168.33333333333326,
					6.66666666666606
				],
				[
					-175,
					6.66666666666606
				],
				[
					-180,
					8.33333333333303
				],
				[
					-180,
					8.33333333333303
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 116,
			"versionNonce": 2126302606,
			"isDeleted": false,
			"id": "KrUy7zLz3yL8IJyKlpcrZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -288.0656565656574,
			"y": 5953.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 18.33333333333394,
			"seed": 1620205330,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666288,
					0
				],
				[
					-6.666666666666629,
					0
				],
				[
					-11.666666666666629,
					-5
				],
				[
					-13.333333333333258,
					-6.66666666666697
				],
				[
					-15,
					-8.33333333333394
				],
				[
					-18.333333333333258,
					-5
				],
				[
					-25,
					1.6666666666660603
				],
				[
					-30,
					8.33333333333303
				],
				[
					-31.66666666666663,
					10
				],
				[
					-38.33333333333326,
					5
				],
				[
					-41.66666666666663,
					1.6666666666660603
				],
				[
					-43.33333333333326,
					0
				],
				[
					-45,
					1.6666666666660603
				],
				[
					-46.66666666666663,
					3.33333333333303
				],
				[
					-46.66666666666663,
					5
				],
				[
					-48.33333333333326,
					8.33333333333303
				],
				[
					-50,
					10
				],
				[
					-55,
					8.33333333333303
				],
				[
					-58.33333333333326,
					5
				],
				[
					-60,
					3.33333333333303
				],
				[
					-61.66666666666663,
					1.6666666666660603
				],
				[
					-65,
					1.6666666666660603
				],
				[
					-70,
					3.33333333333303
				],
				[
					-70,
					3.33333333333303
				],
				[
					-73.33333333333326,
					0
				],
				[
					-76.66666666666674,
					-3.3333333333339397
				],
				[
					-78.33333333333326,
					-5
				],
				[
					-83.33333333333326,
					-3.3333333333339397
				],
				[
					-90,
					-1.6666666666669698
				],
				[
					-93.33333333333326,
					0
				],
				[
					-98.33333333333326,
					1.6666666666660603
				],
				[
					-105,
					1.6666666666660603
				],
				[
					-113.33333333333326,
					3.33333333333303
				],
				[
					-121.66666666666674,
					5
				],
				[
					-130,
					5
				],
				[
					-138.33333333333326,
					5
				],
				[
					-143.33333333333326,
					5
				],
				[
					-151.66666666666674,
					5
				],
				[
					-161.66666666666674,
					5
				],
				[
					-168.33333333333326,
					6.66666666666606
				],
				[
					-175,
					6.66666666666606
				],
				[
					-180,
					8.33333333333303
				],
				[
					-180,
					8.33333333333303
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 121,
			"versionNonce": 1919621714,
			"isDeleted": false,
			"id": "aa59BOdJW_mYfAcO2D6Xb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -266.39898989899086,
			"y": 5706.595238095243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 18.33333333333394,
			"seed": 1034434450,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666288,
					0
				],
				[
					-6.666666666666629,
					0
				],
				[
					-11.666666666666629,
					-5
				],
				[
					-13.333333333333258,
					-6.66666666666697
				],
				[
					-15,
					-8.33333333333394
				],
				[
					-18.333333333333258,
					-5
				],
				[
					-25,
					1.6666666666660603
				],
				[
					-30,
					8.33333333333303
				],
				[
					-31.66666666666663,
					10
				],
				[
					-38.33333333333326,
					5
				],
				[
					-41.66666666666663,
					1.6666666666660603
				],
				[
					-43.33333333333326,
					0
				],
				[
					-45,
					1.6666666666660603
				],
				[
					-46.66666666666663,
					3.33333333333303
				],
				[
					-46.66666666666663,
					5
				],
				[
					-48.33333333333326,
					8.33333333333303
				],
				[
					-50,
					10
				],
				[
					-55,
					8.33333333333303
				],
				[
					-58.33333333333326,
					5
				],
				[
					-60,
					3.33333333333303
				],
				[
					-61.66666666666663,
					1.6666666666660603
				],
				[
					-65,
					1.6666666666660603
				],
				[
					-70,
					3.33333333333303
				],
				[
					-70,
					3.33333333333303
				],
				[
					-73.33333333333326,
					0
				],
				[
					-76.66666666666674,
					-3.3333333333339397
				],
				[
					-78.33333333333326,
					-5
				],
				[
					-83.33333333333326,
					-3.3333333333339397
				],
				[
					-90,
					-1.6666666666669698
				],
				[
					-93.33333333333326,
					0
				],
				[
					-98.33333333333326,
					1.6666666666660603
				],
				[
					-105,
					1.6666666666660603
				],
				[
					-113.33333333333326,
					3.33333333333303
				],
				[
					-121.66666666666674,
					5
				],
				[
					-130,
					5
				],
				[
					-138.33333333333326,
					5
				],
				[
					-143.33333333333326,
					5
				],
				[
					-151.66666666666674,
					5
				],
				[
					-161.66666666666674,
					5
				],
				[
					-168.33333333333326,
					6.66666666666606
				],
				[
					-175,
					6.66666666666606
				],
				[
					-180,
					8.33333333333303
				],
				[
					-180,
					8.33333333333303
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 55,
			"versionNonce": 287828942,
			"isDeleted": false,
			"id": "qNzDysNS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -535.8989898989906,
			"y": 5683.116071428576,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34,
			"height": 54,
			"seed": 1446536398,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 42.91666666666657,
			"fontFamily": 1,
			"text": "V1",
			"rawText": "V1",
			"baseline": 39,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 83,
			"versionNonce": 1719140370,
			"isDeleted": false,
			"id": "TRKma8lS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -529.7323232323239,
			"y": 5928.938988095242,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 53,
			"height": 54,
			"seed": 1007581326,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 42.91666666666657,
			"fontFamily": 1,
			"text": "V2",
			"rawText": "V2",
			"baseline": 39,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 1561674254,
			"isDeleted": false,
			"id": "8ejA2OK2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -559.7323232323239,
			"y": 6140.605654761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 51,
			"height": 54,
			"seed": 2111058382,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 42.91666666666657,
			"fontFamily": 1,
			"text": "V3",
			"rawText": "V3",
			"baseline": 39,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 459419090,
			"isDeleted": false,
			"id": "P4gHyMQZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.2323232323241,
			"y": 5650.095238095242,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 25,
			"seed": 685942734,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R1",
			"rawText": "R1",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 1702744142,
			"isDeleted": false,
			"id": "T7XoRjJl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -354.2323232323241,
			"y": 5890.095238095242,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 25,
			"seed": 1062724946,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R2",
			"rawText": "R2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 373334930,
			"isDeleted": false,
			"id": "TBEaKdaD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380.89898989899075,
			"y": 6106.761904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 25,
			"seed": 1148328846,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R3",
			"rawText": "R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 1715115662,
			"isDeleted": false,
			"id": "yrkc3NT8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 462.4343434343426,
			"y": 5681.761904761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 41,
			"height": 25,
			"seed": 1254126994,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i =0",
			"rawText": "i =0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 558522706,
			"isDeleted": false,
			"id": "ArqbpmHe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 379.10101010100925,
			"y": 5731.761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 25,
			"seed": 1421462994,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V = 0",
			"rawText": "V = 0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 939824334,
			"isDeleted": false,
			"id": "qmlq7Syb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 344.10101010100925,
			"y": 5878.428571428575,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 25,
			"seed": 1367129358,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V = 0",
			"rawText": "V = 0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 668362514,
			"isDeleted": false,
			"id": "ZHwigR2g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 562.4343434343427,
			"y": 5366.761904761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 25,
			"seed": 1465832526,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rf",
			"rawText": "Rf",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 56,
			"versionNonce": 880069390,
			"isDeleted": false,
			"id": "QKIxJgqF7wHUUtmb4V0LU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 925.767676767676,
			"y": 5779.09523809524,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 225.00000000000006,
			"height": 16.66666666666697,
			"seed": 650263758,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					5,
					0
				],
				[
					46.66666666666663,
					3.3333333333339397
				],
				[
					111.66666666666663,
					10
				],
				[
					181.66666666666663,
					16.66666666666697
				],
				[
					213.33333333333337,
					16.66666666666697
				],
				[
					223.33333333333331,
					16.66666666666697
				],
				[
					225.00000000000006,
					16.66666666666697
				],
				[
					225.00000000000006,
					16.66666666666697
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 94,
			"versionNonce": 307999954,
			"isDeleted": false,
			"id": "JvVEDQRVdKE00MAYlzgyo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 899.1010101010095,
			"y": 5420.761904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 171.66666666666663,
			"height": 371.66666666666697,
			"seed": 175930382,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.6666666666666288,
					0
				],
				[
					3.3333333333332575,
					0
				],
				[
					5,
					-1.6666666666669698
				],
				[
					6.666666666666629,
					-1.6666666666669698
				],
				[
					15,
					-1.6666666666669698
				],
				[
					41.66666666666663,
					-1.6666666666669698
				],
				[
					73.33333333333326,
					3.33333333333303
				],
				[
					101.66666666666663,
					3.33333333333303
				],
				[
					125,
					3.33333333333303
				],
				[
					131.66666666666663,
					3.33333333333303
				],
				[
					133.33333333333326,
					5
				],
				[
					133.33333333333326,
					20
				],
				[
					133.33333333333326,
					46.66666666666697
				],
				[
					138.33333333333326,
					81.66666666666697
				],
				[
					143.33333333333326,
					115
				],
				[
					146.66666666666663,
					140
				],
				[
					151.66666666666663,
					160
				],
				[
					155,
					185
				],
				[
					158.33333333333326,
					195
				],
				[
					160,
					213.33333333333303
				],
				[
					161.66666666666663,
					233.33333333333303
				],
				[
					166.66666666666663,
					258.33333333333303
				],
				[
					168.33333333333326,
					266.66666666666697
				],
				[
					170,
					271.66666666666697
				],
				[
					170,
					275
				],
				[
					171.66666666666663,
					280
				],
				[
					171.66666666666663,
					286.66666666666697
				],
				[
					171.66666666666663,
					303.33333333333303
				],
				[
					171.66666666666663,
					315
				],
				[
					171.66666666666663,
					325
				],
				[
					171.66666666666663,
					336.66666666666697
				],
				[
					171.66666666666663,
					343.33333333333303
				],
				[
					171.66666666666663,
					346.66666666666697
				],
				[
					170,
					350
				],
				[
					170,
					351.66666666666697
				],
				[
					168.33333333333326,
					355
				],
				[
					168.33333333333326,
					356.66666666666697
				],
				[
					168.33333333333326,
					358.33333333333303
				],
				[
					170,
					358.33333333333303
				],
				[
					170,
					360
				],
				[
					170,
					361.66666666666697
				],
				[
					170,
					363.33333333333303
				],
				[
					170,
					363.33333333333303
				],
				[
					170,
					366.66666666666697
				],
				[
					170,
					370
				],
				[
					170,
					370
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 436484430,
			"isDeleted": false,
			"id": "hN0GAOpS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -114.73232323232389,
			"y": 6262.178571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 494,
			"height": 74,
			"seed": 2096187474,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0-V1 /R1 + 0-V2/R2 + 0-V3/R3 +0-V0/Rf +0 = 0\n\n",
			"rawText": "0-V1 /R1 + 0-V2/R2 + 0-V3/R3 +0-V0/Rf +0 = 0\n\n",
			"baseline": 67,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 99,
			"versionNonce": 577850002,
			"isDeleted": false,
			"id": "SmtfGDmQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -114.73232323232389,
			"y": 6347.178571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 322,
			"height": 25,
			"seed": 1486551954,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0/Rf = -V1/R1 - V2/R2 - V3/R3",
			"rawText": "V0/Rf = -V1/R1 - V2/R2 - V3/R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 105,
			"versionNonce": 1879826318,
			"isDeleted": false,
			"id": "93JvMQL4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -110.98232323232389,
			"y": 6433.428571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 394,
			"height": 25,
			"seed": 1347671378,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0 = -Rf*V1/R1 - Rf*V2/R2 + Rf*V3/R3",
			"rawText": "V0 = -Rf*V1/R1 - Rf*V2/R2 + Rf*V3/R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 1322133586,
			"isDeleted": false,
			"id": "24qZRyeZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -104.73232323232389,
			"y": 6504.678571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 238,
			"height": 50,
			"seed": 1212416402,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "but Rf = R1 + R2 + R3\n",
			"rawText": "but Rf = R1 + R2 + R3\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 1791278542,
			"isDeleted": false,
			"id": "A8J1Sx8H",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -105.98232323232389,
			"y": 6570.928571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 209,
			"height": 25,
			"seed": 2039708178,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V0 = -(V1 + V2 + V3)",
			"rawText": "V0 = -(V1 + V2 + V3)",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 524897810,
			"isDeleted": false,
			"id": "rxTBzSbZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 430.2676767676761,
			"y": 6442.178571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 209,
			"height": 74,
			"seed": 1150218574,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "here Rf/R* = 1\nso gain is one\nbut we summed stuff",
			"rawText": "here Rf/R* = 1\nso gain is one\nbut we summed stuff",
			"baseline": 67,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "rectangle",
			"version": 60,
			"versionNonce": 1330107406,
			"isDeleted": false,
			"id": "djYItA1iEfmAbL6DsPQTS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -840.4823232323233,
			"y": 4833.678571428572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2300,
			"height": 1935.000000000001,
			"seed": 1173438990,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 148487122,
			"isDeleted": false,
			"id": "SnL9kYJFqYER1L1iFqMfa",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -218.39898989899052,
			"y": 6853.261904761907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 1,
			"seed": 272353106,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 148,
			"versionNonce": 1468932686,
			"isDeleted": false,
			"id": "RHuj33pg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -851.7323232323242,
			"y": 6857.437027511498,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2205,
			"height": 190,
			"seed": 2009370318,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 150.1276595744682,
			"fontFamily": 1,
			"text": "Non inverting Summing amplifier",
			"rawText": "Non inverting Summing amplifier",
			"baseline": 133,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 1234596242,
			"isDeleted": false,
			"id": "Wo1auutn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -423.39898989899075,
			"y": 7157.595238095241,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 190,
			"height": 37,
			"seed": 1068174610,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 29.33333333333358,
			"fontFamily": 1,
			"text": "How to build ",
			"rawText": "How to build ",
			"baseline": 26,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 128,
			"versionNonce": 376481934,
			"isDeleted": false,
			"id": "c8RDGOMXLqS8DWkmRoSmm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 110.76767676767577,
			"y": 7668.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 745,
			"height": 322.66666666666606,
			"seed": 774210830,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					6.666666666666686,
					0
				],
				[
					43.333333333333314,
					-5
				],
				[
					88.33333333333337,
					-6.66666666666606
				],
				[
					148.33333333333337,
					-6.66666666666606
				],
				[
					193.33333333333337,
					-6.66666666666606
				],
				[
					215,
					-5
				],
				[
					221.66666666666669,
					-3.33333333333303
				],
				[
					223.33333333333334,
					-5
				],
				[
					223.33333333333334,
					-8.33333333333303
				],
				[
					223.33333333333334,
					-10
				],
				[
					223.33333333333334,
					-11.66666666666606
				],
				[
					225,
					-15
				],
				[
					225,
					-16.66666666666606
				],
				[
					225,
					-23.33333333333303
				],
				[
					225,
					-38.33333333333303
				],
				[
					225,
					-53.33333333333303
				],
				[
					225,
					-71.66666666666606
				],
				[
					225,
					-91.66666666666606
				],
				[
					225,
					-111.66666666666606
				],
				[
					225,
					-130
				],
				[
					225,
					-148.33333333333303
				],
				[
					225,
					-158.33333333333303
				],
				[
					225,
					-165
				],
				[
					226.66666666666669,
					-171.66666666666606
				],
				[
					226.66666666666669,
					-183.33333333333303
				],
				[
					226.66666666666669,
					-198.33333333333303
				],
				[
					230,
					-210
				],
				[
					231.66666666666669,
					-221.66666666666606
				],
				[
					231.66666666666669,
					-223.33333333333303
				],
				[
					231.66666666666669,
					-225
				],
				[
					231.66666666666669,
					-231.66666666666606
				],
				[
					231.66666666666669,
					-238.33333333333303
				],
				[
					231.66666666666669,
					-243.33333333333303
				],
				[
					230,
					-251.66666666666606
				],
				[
					230,
					-258.33333333333303
				],
				[
					230,
					-261.66666666666606
				],
				[
					230,
					-265
				],
				[
					230,
					-270
				],
				[
					230,
					-271.66666666666606
				],
				[
					230,
					-273.33333333333303
				],
				[
					233.33333333333334,
					-275
				],
				[
					250,
					-273.33333333333303
				],
				[
					298.33333333333337,
					-273.33333333333303
				],
				[
					348.33333333333337,
					-273.33333333333303
				],
				[
					385,
					-273.33333333333303
				],
				[
					386.6666666666667,
					-273.33333333333303
				],
				[
					388.33333333333337,
					-273.33333333333303
				],
				[
					391.6666666666667,
					-275
				],
				[
					398.33333333333337,
					-298.33333333333303
				],
				[
					403.33333333333337,
					-305
				],
				[
					405,
					-306.66666666666606
				],
				[
					406.6666666666667,
					-308.33333333333303
				],
				[
					408.33333333333337,
					-303.33333333333303
				],
				[
					413.33333333333337,
					-290
				],
				[
					416.6666666666667,
					-276.66666666666606
				],
				[
					423.33333333333337,
					-256.66666666666606
				],
				[
					425,
					-255
				],
				[
					426.6666666666667,
					-258.33333333333303
				],
				[
					428.33333333333337,
					-263.33333333333303
				],
				[
					435,
					-276.66666666666606
				],
				[
					440,
					-288.33333333333303
				],
				[
					443.33333333333337,
					-291.66666666666606
				],
				[
					446.6666666666667,
					-291.66666666666606
				],
				[
					451.6666666666667,
					-276.66666666666606
				],
				[
					456.6666666666667,
					-268.33333333333303
				],
				[
					458.33333333333337,
					-265
				],
				[
					463.33333333333337,
					-270
				],
				[
					468.33333333333337,
					-275
				],
				[
					480,
					-291.66666666666606
				],
				[
					498.33333333333337,
					-311.66666666666606
				],
				[
					510,
					-321.66666666666606
				],
				[
					513.3333333333334,
					-318.33333333333303
				],
				[
					516.6666666666667,
					-315
				],
				[
					516.6666666666667,
					-311.66666666666606
				],
				[
					518.3333333333334,
					-306.66666666666606
				],
				[
					520,
					-300
				],
				[
					521.6666666666667,
					-296.66666666666606
				],
				[
					530,
					-295
				],
				[
					550,
					-295
				],
				[
					606.6666666666667,
					-295
				],
				[
					641.6666666666667,
					-295
				],
				[
					735,
					-295
				],
				[
					743.3333333333334,
					-295
				],
				[
					745,
					-295
				],
				[
					745,
					-295
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 63,
			"versionNonce": 1152806738,
			"isDeleted": false,
			"id": "CoPzzRzEFElqOIQhw5Rox",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 330.76767676767577,
			"y": 7659.928571428575,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 146.66666666666669,
			"height": 16.66666666666697,
			"seed": 1420532434,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					3.333333333333343,
					0
				],
				[
					10,
					0
				],
				[
					36.666666666666686,
					6.66666666666697
				],
				[
					61.666666666666686,
					10
				],
				[
					75,
					11.66666666666697
				],
				[
					81.66666666666669,
					11.66666666666697
				],
				[
					86.66666666666669,
					11.66666666666697
				],
				[
					91.66666666666669,
					10
				],
				[
					93.33333333333337,
					10
				],
				[
					96.66666666666669,
					8.33333333333303
				],
				[
					101.66666666666669,
					8.33333333333303
				],
				[
					105,
					8.33333333333303
				],
				[
					106.66666666666669,
					6.66666666666697
				],
				[
					108.33333333333337,
					5
				],
				[
					116.66666666666669,
					3.33333333333303
				],
				[
					130,
					0
				],
				[
					138.33333333333337,
					-1.6666666666669698
				],
				[
					145,
					-3.33333333333303
				],
				[
					146.66666666666669,
					-5
				],
				[
					146.66666666666669,
					-5
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 57,
			"versionNonce": 1537763022,
			"isDeleted": false,
			"id": "l9OlV4NR4eQiEc6KWSQwI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 470.76767676767577,
			"y": 7563.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.666666666666629,
			"height": 291.66666666666697,
			"seed": 1368240974,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					3.3333333333339397
				],
				[
					0,
					11.66666666666697
				],
				[
					3.3333333333333712,
					25
				],
				[
					5,
					58.33333333333394
				],
				[
					5,
					103.33333333333394
				],
				[
					5,
					146.66666666666697
				],
				[
					-3.3333333333333144,
					223.33333333333394
				],
				[
					-6.666666666666629,
					250
				],
				[
					-6.666666666666629,
					268.33333333333394
				],
				[
					-3.3333333333333144,
					281.66666666666697
				],
				[
					1.6666666666666856,
					290
				],
				[
					1.6666666666666856,
					291.66666666666697
				],
				[
					0,
					290
				],
				[
					0,
					290
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 80,
			"versionNonce": 1586541842,
			"isDeleted": false,
			"id": "i7wEyqKS0Z0XrqozYSG-Z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 460.76767676767577,
			"y": 7558.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 411.66666666666674,
			"height": 176.66666666666697,
			"seed": 500461714,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.6666666666666856,
					1.6666666666669698
				],
				[
					3.3333333333333712,
					1.6666666666669698
				],
				[
					10,
					5
				],
				[
					16.666666666666686,
					8.33333333333394
				],
				[
					26.666666666666686,
					13.33333333333394
				],
				[
					38.33333333333337,
					21.66666666666697
				],
				[
					51.666666666666686,
					30
				],
				[
					83.33333333333337,
					45
				],
				[
					116.66666666666669,
					55
				],
				[
					145,
					65
				],
				[
					176.66666666666669,
					75
				],
				[
					193.33333333333337,
					81.66666666666697
				],
				[
					208.33333333333337,
					88.33333333333394
				],
				[
					215,
					93.33333333333394
				],
				[
					221.66666666666674,
					96.66666666666697
				],
				[
					230,
					100
				],
				[
					243.33333333333337,
					103.33333333333394
				],
				[
					253.33333333333337,
					106.66666666666697
				],
				[
					260,
					110
				],
				[
					263.33333333333337,
					113.33333333333394
				],
				[
					273.33333333333337,
					123.33333333333394
				],
				[
					288.33333333333337,
					131.66666666666697
				],
				[
					300,
					135
				],
				[
					315,
					140
				],
				[
					320,
					141.66666666666697
				],
				[
					323.33333333333337,
					143.33333333333394
				],
				[
					330,
					148.33333333333394
				],
				[
					343.33333333333337,
					153.33333333333394
				],
				[
					371.66666666666674,
					160
				],
				[
					393.33333333333337,
					166.66666666666697
				],
				[
					396.66666666666674,
					168.33333333333394
				],
				[
					400,
					170
				],
				[
					403.33333333333337,
					171.66666666666697
				],
				[
					406.66666666666674,
					173.33333333333394
				],
				[
					410,
					175
				],
				[
					411.66666666666674,
					176.66666666666697
				],
				[
					411.66666666666674,
					176.66666666666697
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 84,
			"versionNonce": 399400206,
			"isDeleted": false,
			"id": "cVn1hfFfmdJfEl0XfIc6w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 467.4343434343425,
			"y": 7849.928571428575,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 403.3333333333333,
			"height": 117.66666666666697,
			"seed": 743840142,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					5,
					0
				],
				[
					46.666666666666686,
					-8.33333333333303
				],
				[
					98.33333333333331,
					-25
				],
				[
					143.33333333333331,
					-33.33333333333303
				],
				[
					178.33333333333331,
					-43.33333333333303
				],
				[
					191.66666666666669,
					-46.66666666666697
				],
				[
					201.66666666666669,
					-53.33333333333303
				],
				[
					210.00000000000006,
					-58.33333333333303
				],
				[
					223.33333333333331,
					-65
				],
				[
					236.66666666666669,
					-70
				],
				[
					245.00000000000006,
					-75
				],
				[
					251.66666666666669,
					-78.33333333333303
				],
				[
					266.6666666666667,
					-88.33333333333303
				],
				[
					278.3333333333333,
					-91.66666666666697
				],
				[
					286.6666666666667,
					-96.66666666666697
				],
				[
					295.00000000000006,
					-100
				],
				[
					298.3333333333333,
					-101.66666666666697
				],
				[
					300.00000000000006,
					-101.66666666666697
				],
				[
					303.3333333333333,
					-101.66666666666697
				],
				[
					306.6666666666667,
					-101.66666666666697
				],
				[
					311.6666666666667,
					-101.66666666666697
				],
				[
					316.6666666666667,
					-101.66666666666697
				],
				[
					321.6666666666667,
					-101.66666666666697
				],
				[
					326.6666666666667,
					-103.33333333333303
				],
				[
					330.00000000000006,
					-105
				],
				[
					336.6666666666667,
					-106.66666666666697
				],
				[
					341.6666666666667,
					-108.33333333333303
				],
				[
					343.3333333333333,
					-108.33333333333303
				],
				[
					348.3333333333333,
					-110
				],
				[
					358.3333333333333,
					-111.66666666666697
				],
				[
					363.3333333333333,
					-113.33333333333303
				],
				[
					366.6666666666667,
					-113.33333333333303
				],
				[
					373.3333333333333,
					-113.33333333333303
				],
				[
					378.3333333333333,
					-115
				],
				[
					381.6666666666667,
					-115
				],
				[
					393.3333333333333,
					-116.66666666666697
				],
				[
					396.6666666666667,
					-116.66666666666697
				],
				[
					400.00000000000006,
					-116.66666666666697
				],
				[
					401.6666666666667,
					-116.66666666666697
				],
				[
					403.3333333333333,
					-116.66666666666697
				],
				[
					403.3333333333333,
					-116.66666666666697
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 49,
			"versionNonce": 1486635730,
			"isDeleted": false,
			"id": "qFeMA8MWOXgxHCqGsU4OH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 504.10101010100914,
			"y": 7651.595238095241,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.333333333333314,
			"height": 1,
			"seed": 2128383570,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					3.3333333333333144,
					0
				],
				[
					8.333333333333314,
					0
				],
				[
					25,
					0
				],
				[
					35,
					0
				],
				[
					38.333333333333314,
					0
				],
				[
					38.333333333333314,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 57,
			"versionNonce": 1079741262,
			"isDeleted": false,
			"id": "jXdYOPbOtoyFPw3YHkLg-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 459.101010101009,
			"y": 7798.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 292.6666666666667,
			"height": 16.66666666666606,
			"seed": 1438103502,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-8.333333333333314,
					0
				],
				[
					-66.66666666666663,
					3.33333333333303
				],
				[
					-143.33333333333331,
					3.33333333333303
				],
				[
					-210,
					6.66666666666606
				],
				[
					-248.33333333333331,
					11.66666666666606
				],
				[
					-256.66666666666663,
					11.66666666666606
				],
				[
					-260,
					13.33333333333303
				],
				[
					-265,
					15
				],
				[
					-270,
					16.66666666666606
				],
				[
					-280,
					16.66666666666606
				],
				[
					-288.3333333333333,
					16.66666666666606
				],
				[
					-291.6666666666667,
					16.66666666666606
				],
				[
					-291.6666666666667,
					16.66666666666606
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 47,
			"versionNonce": 762321042,
			"isDeleted": false,
			"id": "vijj6Jr5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 500.76767676767577,
			"y": 7756.954212454218,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 51,
			"seed": 1285223442,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 40.512820512820475,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 36,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 130,
			"versionNonce": 1824732754,
			"isDeleted": false,
			"id": "DkyoraaCHplfbS2PmRoul",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5463875803992444,
			"x": 127.59420853825941,
			"y": 7671.871293726182,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 61,
			"height": 2.66666666666697,
			"seed": 688300498,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-3.3333333333333144,
					-1.6666666666669698
				],
				[
					-10,
					-1.6666666666669698
				],
				[
					-18.333333333333314,
					-1.6666666666669698
				],
				[
					-30,
					-1.6666666666669698
				],
				[
					-46.666666666666686,
					-1.6666666666669698
				],
				[
					-56.666666666666686,
					0
				],
				[
					-58.333333333333314,
					0
				],
				[
					-60,
					0
				],
				[
					-60,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 127,
			"versionNonce": 485461966,
			"isDeleted": false,
			"id": "0fWi4hHIambm7S_zpwHqb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5463875803992444,
			"x": 78.19216677186654,
			"y": 7661.752790259151,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21,
			"height": 1,
			"seed": 1233820750,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-3.3333333333333144,
					0
				],
				[
					-6.666666666666686,
					0
				],
				[
					-15,
					0
				],
				[
					-18.333333333333314,
					0
				],
				[
					-20,
					0
				],
				[
					-20,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 128,
			"versionNonce": 392993810,
			"isDeleted": false,
			"id": "7UdkjP-GeGj2R1ikE4SWy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 1.5463875803992444,
			"x": 57.965342154929345,
			"y": 7665.146117982245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.666666666666686,
			"height": 3.33333333333303,
			"seed": 1597413266,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					1.6666666666669698
				],
				[
					-3.3333333333333144,
					3.33333333333303
				],
				[
					-6.666666666666686,
					3.33333333333303
				],
				[
					-10,
					3.33333333333303
				],
				[
					-11.666666666666686,
					3.33333333333303
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 162,
			"versionNonce": 1481139726,
			"isDeleted": false,
			"id": "CRFtWaNanCNqbJ2QV8_9u",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 194.43434343434228,
			"y": 7812.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 502.6666666666667,
			"height": 458.33333333333303,
			"seed": 1187897998,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666856,
					0
				],
				[
					-13.333333333333314,
					0
				],
				[
					-56.666666666666686,
					0
				],
				[
					-104.99999999999994,
					0
				],
				[
					-128.33333333333331,
					0
				],
				[
					-183.33333333333331,
					0
				],
				[
					-196.66666666666669,
					3.3333333333339397
				],
				[
					-200.00000000000006,
					3.3333333333339397
				],
				[
					-201.66666666666669,
					3.3333333333339397
				],
				[
					-203.33333333333331,
					3.3333333333339397
				],
				[
					-211.66666666666669,
					3.3333333333339397
				],
				[
					-230.00000000000006,
					-1.6666666666660603
				],
				[
					-240.00000000000006,
					-1.6666666666660603
				],
				[
					-258.3333333333333,
					-1.6666666666660603
				],
				[
					-271.6666666666667,
					-3.33333333333303
				],
				[
					-275.00000000000006,
					-3.33333333333303
				],
				[
					-276.6666666666667,
					-3.33333333333303
				],
				[
					-278.3333333333333,
					-3.33333333333303
				],
				[
					-283.3333333333333,
					-3.33333333333303
				],
				[
					-293.3333333333333,
					-3.33333333333303
				],
				[
					-303.3333333333333,
					-3.33333333333303
				],
				[
					-310.00000000000006,
					-3.33333333333303
				],
				[
					-315.00000000000006,
					-3.33333333333303
				],
				[
					-316.6666666666667,
					-3.33333333333303
				],
				[
					-318.3333333333333,
					-3.33333333333303
				],
				[
					-320.00000000000006,
					-3.33333333333303
				],
				[
					-320.00000000000006,
					-3.33333333333303
				],
				[
					-321.6666666666667,
					-3.33333333333303
				],
				[
					-321.6666666666667,
					-1.6666666666660603
				],
				[
					-321.6666666666667,
					10
				],
				[
					-321.6666666666667,
					31.66666666666697
				],
				[
					-321.6666666666667,
					95
				],
				[
					-321.6666666666667,
					205
				],
				[
					-321.6666666666667,
					311.66666666666697
				],
				[
					-321.6666666666667,
					366.66666666666697
				],
				[
					-323.3333333333333,
					381.66666666666697
				],
				[
					-325.00000000000006,
					395
				],
				[
					-328.3333333333333,
					411.66666666666697
				],
				[
					-330.00000000000006,
					416.66666666666697
				],
				[
					-330.00000000000006,
					421.66666666666697
				],
				[
					-331.6666666666667,
					426.66666666666697
				],
				[
					-331.6666666666667,
					428.33333333333394
				],
				[
					-331.6666666666667,
					430
				],
				[
					-331.6666666666667,
					430
				],
				[
					-330.00000000000006,
					438.33333333333394
				],
				[
					-330.00000000000006,
					441.66666666666697
				],
				[
					-330.00000000000006,
					443.33333333333394
				],
				[
					-330.00000000000006,
					445
				],
				[
					-330.00000000000006,
					446.66666666666697
				],
				[
					-330.00000000000006,
					448.33333333333394
				],
				[
					-330.00000000000006,
					448.33333333333394
				],
				[
					-330.00000000000006,
					450
				],
				[
					-330.00000000000006,
					450
				],
				[
					-338.3333333333333,
					451.66666666666697
				],
				[
					-355.00000000000006,
					455
				],
				[
					-381.6666666666667,
					455
				],
				[
					-413.3333333333334,
					455
				],
				[
					-448.3333333333334,
					455
				],
				[
					-483.3333333333334,
					455
				],
				[
					-488.3333333333334,
					455
				],
				[
					-495.00000000000006,
					455
				],
				[
					-498.3333333333334,
					455
				],
				[
					-501.6666666666667,
					455
				],
				[
					-501.6666666666667,
					455
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 100,
			"versionNonce": 2070104530,
			"isDeleted": false,
			"id": "FboSoFWvKmT-joAUJqWHw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -127.23232323232423,
			"y": 8058.928571428577,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 144.33333333333326,
			"height": 9.33333333333394,
			"seed": 1063376210,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-3.3333333333332575,
					0
				],
				[
					-11.666666666666629,
					0
				],
				[
					-20,
					0
				],
				[
					-36.66666666666663,
					-1.6666666666669698
				],
				[
					-58.33333333333326,
					-5
				],
				[
					-76.66666666666663,
					-6.66666666666697
				],
				[
					-86.66666666666663,
					-6.66666666666697
				],
				[
					-101.66666666666663,
					-6.66666666666697
				],
				[
					-113.33333333333326,
					-6.66666666666697
				],
				[
					-130,
					-6.66666666666697
				],
				[
					-141.66666666666663,
					-8.33333333333394
				],
				[
					-143.33333333333326,
					-8.33333333333394
				],
				[
					-143.33333333333326,
					-8.33333333333394
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 109,
			"versionNonce": 1454142542,
			"isDeleted": false,
			"id": "DsBgxzXKprDSKTre_1QJH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.56565656565772,
			"y": 7807.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 117.66666666666674,
			"height": 2.66666666666697,
			"seed": 1078878414,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666667425,
					0
				],
				[
					-3.3333333333333712,
					0
				],
				[
					-15,
					0
				],
				[
					-46.66666666666674,
					0
				],
				[
					-66.66666666666674,
					0
				],
				[
					-76.66666666666674,
					0
				],
				[
					-81.66666666666674,
					0
				],
				[
					-83.33333333333337,
					0
				],
				[
					-85,
					0
				],
				[
					-86.66666666666674,
					0
				],
				[
					-90,
					0
				],
				[
					-91.66666666666674,
					0
				],
				[
					-95,
					0
				],
				[
					-98.33333333333337,
					-1.6666666666669698
				],
				[
					-101.66666666666674,
					-1.6666666666669698
				],
				[
					-106.66666666666674,
					-1.6666666666669698
				],
				[
					-110,
					-1.6666666666669698
				],
				[
					-113.33333333333337,
					-1.6666666666669698
				],
				[
					-115,
					-1.6666666666669698
				],
				[
					-115,
					-1.6666666666669698
				],
				[
					-116.66666666666674,
					-1.6666666666669698
				],
				[
					-116.66666666666674,
					-1.6666666666669698
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 130,
			"versionNonce": 264126354,
			"isDeleted": false,
			"id": "HzQMVWw4e0IvJpx0d7LYn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -312.23232323232423,
			"y": 8263.928571428576,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 18.33333333333394,
			"seed": 2061458194,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666288,
					0
				],
				[
					-6.666666666666629,
					0
				],
				[
					-11.666666666666629,
					-5
				],
				[
					-13.333333333333258,
					-6.66666666666697
				],
				[
					-15,
					-8.33333333333394
				],
				[
					-18.333333333333258,
					-5
				],
				[
					-25,
					1.6666666666660603
				],
				[
					-30,
					8.33333333333303
				],
				[
					-31.66666666666663,
					10
				],
				[
					-38.33333333333326,
					5
				],
				[
					-41.66666666666663,
					1.6666666666660603
				],
				[
					-43.33333333333326,
					0
				],
				[
					-45,
					1.6666666666660603
				],
				[
					-46.66666666666663,
					3.33333333333303
				],
				[
					-46.66666666666663,
					5
				],
				[
					-48.33333333333326,
					8.33333333333303
				],
				[
					-50,
					10
				],
				[
					-55,
					8.33333333333303
				],
				[
					-58.33333333333326,
					5
				],
				[
					-60,
					3.33333333333303
				],
				[
					-61.66666666666663,
					1.6666666666660603
				],
				[
					-65,
					1.6666666666660603
				],
				[
					-70,
					3.33333333333303
				],
				[
					-70,
					3.33333333333303
				],
				[
					-73.33333333333326,
					0
				],
				[
					-76.66666666666674,
					-3.3333333333339397
				],
				[
					-78.33333333333326,
					-5
				],
				[
					-83.33333333333326,
					-3.3333333333339397
				],
				[
					-90,
					-1.6666666666669698
				],
				[
					-93.33333333333326,
					0
				],
				[
					-98.33333333333326,
					1.6666666666660603
				],
				[
					-105,
					1.6666666666660603
				],
				[
					-113.33333333333326,
					3.33333333333303
				],
				[
					-121.66666666666674,
					5
				],
				[
					-130,
					5
				],
				[
					-138.33333333333326,
					5
				],
				[
					-143.33333333333326,
					5
				],
				[
					-151.66666666666674,
					5
				],
				[
					-161.66666666666674,
					5
				],
				[
					-168.33333333333326,
					6.66666666666606
				],
				[
					-175,
					6.66666666666606
				],
				[
					-180,
					8.33333333333303
				],
				[
					-180,
					8.33333333333303
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 155,
			"versionNonce": 32815758,
			"isDeleted": false,
			"id": "t_njStzT6kurgxJ78q50C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -271.0656565656577,
			"y": 8049.761904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 18.33333333333394,
			"seed": 698685198,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666288,
					0
				],
				[
					-6.666666666666629,
					0
				],
				[
					-11.666666666666629,
					-5
				],
				[
					-13.333333333333258,
					-6.66666666666697
				],
				[
					-15,
					-8.33333333333394
				],
				[
					-18.333333333333258,
					-5
				],
				[
					-25,
					1.6666666666660603
				],
				[
					-30,
					8.33333333333303
				],
				[
					-31.66666666666663,
					10
				],
				[
					-38.33333333333326,
					5
				],
				[
					-41.66666666666663,
					1.6666666666660603
				],
				[
					-43.33333333333326,
					0
				],
				[
					-45,
					1.6666666666660603
				],
				[
					-46.66666666666663,
					3.33333333333303
				],
				[
					-46.66666666666663,
					5
				],
				[
					-48.33333333333326,
					8.33333333333303
				],
				[
					-50,
					10
				],
				[
					-55,
					8.33333333333303
				],
				[
					-58.33333333333326,
					5
				],
				[
					-60,
					3.33333333333303
				],
				[
					-61.66666666666663,
					1.6666666666660603
				],
				[
					-65,
					1.6666666666660603
				],
				[
					-70,
					3.33333333333303
				],
				[
					-70,
					3.33333333333303
				],
				[
					-73.33333333333326,
					0
				],
				[
					-76.66666666666674,
					-3.3333333333339397
				],
				[
					-78.33333333333326,
					-5
				],
				[
					-83.33333333333326,
					-3.3333333333339397
				],
				[
					-90,
					-1.6666666666669698
				],
				[
					-93.33333333333326,
					0
				],
				[
					-98.33333333333326,
					1.6666666666660603
				],
				[
					-105,
					1.6666666666660603
				],
				[
					-113.33333333333326,
					3.33333333333303
				],
				[
					-121.66666666666674,
					5
				],
				[
					-130,
					5
				],
				[
					-138.33333333333326,
					5
				],
				[
					-143.33333333333326,
					5
				],
				[
					-151.66666666666674,
					5
				],
				[
					-161.66666666666674,
					5
				],
				[
					-168.33333333333326,
					6.66666666666606
				],
				[
					-175,
					6.66666666666606
				],
				[
					-180,
					8.33333333333303
				],
				[
					-180,
					8.33333333333303
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 160,
			"versionNonce": 1354005842,
			"isDeleted": false,
			"id": "TyMeBWV7k2fm05JemHtQf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -249.3989898989912,
			"y": 7803.095238095245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181,
			"height": 18.33333333333394,
			"seed": 2500818,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-1.6666666666666288,
					0
				],
				[
					-6.666666666666629,
					0
				],
				[
					-11.666666666666629,
					-5
				],
				[
					-13.333333333333258,
					-6.66666666666697
				],
				[
					-15,
					-8.33333333333394
				],
				[
					-18.333333333333258,
					-5
				],
				[
					-25,
					1.6666666666660603
				],
				[
					-30,
					8.33333333333303
				],
				[
					-31.66666666666663,
					10
				],
				[
					-38.33333333333326,
					5
				],
				[
					-41.66666666666663,
					1.6666666666660603
				],
				[
					-43.33333333333326,
					0
				],
				[
					-45,
					1.6666666666660603
				],
				[
					-46.66666666666663,
					3.33333333333303
				],
				[
					-46.66666666666663,
					5
				],
				[
					-48.33333333333326,
					8.33333333333303
				],
				[
					-50,
					10
				],
				[
					-55,
					8.33333333333303
				],
				[
					-58.33333333333326,
					5
				],
				[
					-60,
					3.33333333333303
				],
				[
					-61.66666666666663,
					1.6666666666660603
				],
				[
					-65,
					1.6666666666660603
				],
				[
					-70,
					3.33333333333303
				],
				[
					-70,
					3.33333333333303
				],
				[
					-73.33333333333326,
					0
				],
				[
					-76.66666666666674,
					-3.3333333333339397
				],
				[
					-78.33333333333326,
					-5
				],
				[
					-83.33333333333326,
					-3.3333333333339397
				],
				[
					-90,
					-1.6666666666669698
				],
				[
					-93.33333333333326,
					0
				],
				[
					-98.33333333333326,
					1.6666666666660603
				],
				[
					-105,
					1.6666666666660603
				],
				[
					-113.33333333333326,
					3.33333333333303
				],
				[
					-121.66666666666674,
					5
				],
				[
					-130,
					5
				],
				[
					-138.33333333333326,
					5
				],
				[
					-143.33333333333326,
					5
				],
				[
					-151.66666666666674,
					5
				],
				[
					-161.66666666666674,
					5
				],
				[
					-168.33333333333326,
					6.66666666666606
				],
				[
					-175,
					6.66666666666606
				],
				[
					-180,
					8.33333333333303
				],
				[
					-180,
					8.33333333333303
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 551172302,
			"isDeleted": false,
			"id": "EMEIy39O",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -518.8989898989907,
			"y": 7779.616071428577,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34,
			"height": 54,
			"seed": 457901390,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 42.91666666666657,
			"fontFamily": 1,
			"text": "V1",
			"rawText": "V1",
			"baseline": 39,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 463274770,
			"isDeleted": false,
			"id": "8ImNs7s3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -512.7323232323242,
			"y": 8025.438988095243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 53,
			"height": 54,
			"seed": 1456291474,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 42.91666666666657,
			"fontFamily": 1,
			"text": "V2",
			"rawText": "V2",
			"baseline": 39,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 128,
			"versionNonce": 989196046,
			"isDeleted": false,
			"id": "QOjv5tJs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -542.7323232323242,
			"y": 8237.105654761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 51,
			"height": 54,
			"seed": 916007822,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 42.91666666666657,
			"fontFamily": 1,
			"text": "V3",
			"rawText": "V3",
			"baseline": 39,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 183423186,
			"isDeleted": false,
			"id": "MYAtsSLh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -312.23232323232423,
			"y": 7746.595238095243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 25,
			"seed": 2072747090,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R1",
			"rawText": "R1",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 2093014350,
			"isDeleted": false,
			"id": "LP3TLGME",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -337.23232323232423,
			"y": 7986.595238095243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 25,
			"seed": 164137422,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R2",
			"rawText": "R2",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 1379985042,
			"isDeleted": false,
			"id": "4LSo8Gpj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -363.898989898991,
			"y": 8203.261904761908,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 25,
			"seed": 1010319890,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R3",
			"rawText": "R3",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 462685070,
			"isDeleted": false,
			"id": "pg2KHxE8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 397.4343434343424,
			"y": 7634.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 41,
			"height": 25,
			"seed": 1945247758,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "i =0",
			"rawText": "i =0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 441074770,
			"isDeleted": false,
			"id": "S8JSbz8o",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 314.101010101009,
			"y": 7684.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 25,
			"seed": 332017618,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V = 0",
			"rawText": "V = 0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 967336398,
			"isDeleted": false,
			"id": "Mxi9IVXL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 279.101010101009,
			"y": 7830.928571428577,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 25,
			"seed": 151973454,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V = 0",
			"rawText": "V = 0",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 1558309394,
			"isDeleted": false,
			"id": "A0IMgOfE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 497.4343434343425,
			"y": 7319.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 25,
			"seed": 106456466,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rf",
			"rawText": "Rf",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 46,
			"versionNonce": 1243019278,
			"isDeleted": false,
			"id": "8uVvI7rvGyEe1xUeNZ0I1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 860.7676767676758,
			"y": 7731.595238095241,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 225.00000000000006,
			"height": 16.66666666666697,
			"seed": 1979184270,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					5,
					0
				],
				[
					46.66666666666663,
					3.3333333333339397
				],
				[
					111.66666666666663,
					10
				],
				[
					181.66666666666663,
					16.66666666666697
				],
				[
					213.33333333333337,
					16.66666666666697
				],
				[
					223.33333333333331,
					16.66666666666697
				],
				[
					225.00000000000006,
					16.66666666666697
				],
				[
					225.00000000000006,
					16.66666666666697
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 84,
			"versionNonce": 1090443218,
			"isDeleted": false,
			"id": "TG6brOJQAqbozRhdbfRJ-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 834.1010101010093,
			"y": 7373.261904761909,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 171.66666666666663,
			"height": 371.66666666666697,
			"seed": 2098848594,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					1.6666666666666288,
					0
				],
				[
					3.3333333333332575,
					0
				],
				[
					5,
					-1.6666666666669698
				],
				[
					6.666666666666629,
					-1.6666666666669698
				],
				[
					15,
					-1.6666666666669698
				],
				[
					41.66666666666663,
					-1.6666666666669698
				],
				[
					73.33333333333326,
					3.33333333333303
				],
				[
					101.66666666666663,
					3.33333333333303
				],
				[
					125,
					3.33333333333303
				],
				[
					131.66666666666663,
					3.33333333333303
				],
				[
					133.33333333333326,
					5
				],
				[
					133.33333333333326,
					20
				],
				[
					133.33333333333326,
					46.66666666666697
				],
				[
					138.33333333333326,
					81.66666666666697
				],
				[
					143.33333333333326,
					115
				],
				[
					146.66666666666663,
					140
				],
				[
					151.66666666666663,
					160
				],
				[
					155,
					185
				],
				[
					158.33333333333326,
					195
				],
				[
					160,
					213.33333333333303
				],
				[
					161.66666666666663,
					233.33333333333303
				],
				[
					166.66666666666663,
					258.33333333333303
				],
				[
					168.33333333333326,
					266.66666666666697
				],
				[
					170,
					271.66666666666697
				],
				[
					170,
					275
				],
				[
					171.66666666666663,
					280
				],
				[
					171.66666666666663,
					286.66666666666697
				],
				[
					171.66666666666663,
					303.33333333333303
				],
				[
					171.66666666666663,
					315
				],
				[
					171.66666666666663,
					325
				],
				[
					171.66666666666663,
					336.66666666666697
				],
				[
					171.66666666666663,
					343.33333333333303
				],
				[
					171.66666666666663,
					346.66666666666697
				],
				[
					170,
					350
				],
				[
					170,
					351.66666666666697
				],
				[
					168.33333333333326,
					355
				],
				[
					168.33333333333326,
					356.66666666666697
				],
				[
					168.33333333333326,
					358.33333333333303
				],
				[
					170,
					358.33333333333303
				],
				[
					170,
					360
				],
				[
					170,
					361.66666666666697
				],
				[
					170,
					363.33333333333303
				],
				[
					170,
					363.33333333333303
				],
				[
					170,
					366.66666666666697
				],
				[
					170,
					370
				],
				[
					170,
					370
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "rectangle",
			"version": 50,
			"versionNonce": 1877704974,
			"isDeleted": false,
			"id": "mEp9cacMzqkdVzBAOluwr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -905.4823232323236,
			"y": 6786.178571428573,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2300,
			"height": 1935.000000000001,
			"seed": 1596603790,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": []
		},
		{
			"type": "freedraw",
			"version": 52,
			"versionNonce": 2001952466,
			"isDeleted": false,
			"id": "9anwPFN_Z8Dr35IKc_J4d",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 171.29545454545462,
			"y": 7662.678571428571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 96,
			"height": 24,
			"seed": 960211214,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					4,
					0
				],
				[
					14,
					-4
				],
				[
					16,
					-6
				],
				[
					22,
					-8
				],
				[
					26,
					-12
				],
				[
					28,
					-14
				],
				[
					28,
					-10
				],
				[
					28,
					-4
				],
				[
					28,
					-2
				],
				[
					28,
					0
				],
				[
					30,
					4
				],
				[
					30,
					6
				],
				[
					34,
					4
				],
				[
					38,
					0
				],
				[
					40,
					-2
				],
				[
					44,
					-10
				],
				[
					46,
					-14
				],
				[
					48,
					-16
				],
				[
					48,
					-16
				],
				[
					50,
					-16
				],
				[
					54,
					-12
				],
				[
					56,
					-10
				],
				[
					58,
					-6
				],
				[
					60,
					-4
				],
				[
					62,
					0
				],
				[
					62,
					2
				],
				[
					64,
					6
				],
				[
					64,
					8
				],
				[
					66,
					6
				],
				[
					68,
					2
				],
				[
					68,
					-2
				],
				[
					70,
					-6
				],
				[
					70,
					-8
				],
				[
					72,
					-10
				],
				[
					74,
					-12
				],
				[
					76,
					-8
				],
				[
					80,
					-6
				],
				[
					84,
					-4
				],
				[
					86,
					-2
				],
				[
					88,
					0
				],
				[
					90,
					0
				],
				[
					92,
					0
				],
				[
					94,
					0
				],
				[
					96,
					0
				],
				[
					96,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 4,
			"versionNonce": 1404728206,
			"isDeleted": false,
			"id": "lnVEVndF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 193.29545454545462,
			"y": 7587.678571428571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 25,
			"seed": 344678610,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R5",
			"rawText": "R5",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "freedraw",
			"version": 107,
			"versionNonce": 559448722,
			"isDeleted": false,
			"id": "XeOZbnjHIkd2vH6otgNjC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 173.29545454545462,
			"y": 7808.678571428571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 494,
			"seed": 2114657554,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					4
				],
				[
					0,
					24
				],
				[
					0,
					48
				],
				[
					0,
					62
				],
				[
					0,
					78
				],
				[
					0,
					88
				],
				[
					0,
					98
				],
				[
					0,
					106
				],
				[
					0,
					112
				],
				[
					0,
					120
				],
				[
					0,
					142
				],
				[
					2,
					154
				],
				[
					4,
					162
				],
				[
					4,
					166
				],
				[
					4,
					170
				],
				[
					4,
					174
				],
				[
					4,
					176
				],
				[
					4,
					178
				],
				[
					4,
					188
				],
				[
					4,
					192
				],
				[
					8,
					218
				],
				[
					8,
					230
				],
				[
					10,
					236
				],
				[
					10,
					240
				],
				[
					8,
					242
				],
				[
					10,
					244
				],
				[
					18,
					246
				],
				[
					22,
					248
				],
				[
					28,
					248
				],
				[
					32,
					250
				],
				[
					14,
					262
				],
				[
					10,
					264
				],
				[
					-6,
					270
				],
				[
					-18,
					276
				],
				[
					-24,
					280
				],
				[
					-28,
					282
				],
				[
					-26,
					282
				],
				[
					-18,
					282
				],
				[
					-6,
					282
				],
				[
					4,
					284
				],
				[
					6,
					284
				],
				[
					8,
					286
				],
				[
					10,
					288
				],
				[
					16,
					290
				],
				[
					20,
					292
				],
				[
					22,
					294
				],
				[
					24,
					294
				],
				[
					26,
					294
				],
				[
					28,
					296
				],
				[
					30,
					296
				],
				[
					32,
					296
				],
				[
					32,
					296
				],
				[
					30,
					298
				],
				[
					24,
					300
				],
				[
					16,
					302
				],
				[
					14,
					304
				],
				[
					12,
					306
				],
				[
					10,
					308
				],
				[
					8,
					310
				],
				[
					6,
					312
				],
				[
					2,
					314
				],
				[
					0,
					316
				],
				[
					-2,
					316
				],
				[
					-2,
					318
				],
				[
					-2,
					322
				],
				[
					-4,
					324
				],
				[
					-4,
					326
				],
				[
					-2,
					330
				],
				[
					2,
					330
				],
				[
					10,
					330
				],
				[
					18,
					330
				],
				[
					26,
					330
				],
				[
					28,
					330
				],
				[
					30,
					330
				],
				[
					30,
					330
				],
				[
					30,
					332
				],
				[
					26,
					336
				],
				[
					20,
					340
				],
				[
					16,
					342
				],
				[
					14,
					344
				],
				[
					12,
					346
				],
				[
					10,
					346
				],
				[
					10,
					348
				],
				[
					10,
					352
				],
				[
					10,
					358
				],
				[
					10,
					364
				],
				[
					10,
					374
				],
				[
					12,
					402
				],
				[
					12,
					412
				],
				[
					12,
					416
				],
				[
					12,
					420
				],
				[
					10,
					422
				],
				[
					10,
					424
				],
				[
					10,
					432
				],
				[
					10,
					436
				],
				[
					10,
					448
				],
				[
					10,
					476
				],
				[
					8,
					484
				],
				[
					8,
					488
				],
				[
					8,
					492
				],
				[
					8,
					494
				],
				[
					8,
					494
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 542386062,
			"isDeleted": false,
			"id": "MwJX3-09eiWfcdCVNC7AN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 207.29545454545462,
			"y": 8302.67857142857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 49,
			"height": 3,
			"seed": 1536219154,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					0
				],
				[
					-10,
					0
				],
				[
					-18,
					-2
				],
				[
					-22,
					-2
				],
				[
					-24,
					-2
				],
				[
					-28,
					-2
				],
				[
					-40,
					-2
				],
				[
					-44,
					-2
				],
				[
					-46,
					-2
				],
				[
					-46,
					-2
				],
				[
					-48,
					0
				],
				[
					-48,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1544446034,
			"isDeleted": false,
			"id": "c3l7uU0QYR1VvdVDVECCC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.29545454545462,
			"y": 8336.67857142857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 1,
			"seed": 2026504274,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-12,
					0
				],
				[
					-16,
					0
				],
				[
					-18,
					0
				],
				[
					-18,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 2059666894,
			"isDeleted": false,
			"id": "UG6shCXzVDKHauE6NCLAh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.29545454545462,
			"y": 8354.67857142857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17,
			"height": 2,
			"seed": 101074770,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElementIds": [],
			"points": [
				[
					0,
					0
				],
				[
					1,
					1,
					0.5
				],
				[
					0,
					2
				],
				[
					-4,
					2
				],
				[
					-10,
					2
				],
				[
					-14,
					2
				],
				[
					-16,
					2
				],
				[
					-16,
					2
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 4,
			"versionNonce": 2005408846,
			"isDeleted": false,
			"id": "2CY1i2XD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 265.2954545454546,
			"y": 8085.678571428571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 25,
			"seed": 1406497810,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R4",
			"rawText": "R4",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 196,
			"versionNonce": 994603986,
			"isDeleted": false,
			"id": "sK1LWuRl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 555.8668831168833,
			"y": 7999.107142857145,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 558,
			"height": 223,
			"seed": 946974158,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "V - V1 / R1 + V-V2/R2 + V-V3/R3 + V-0/R4 = 0\n\nV-0 / R5 + V-V0/Rf + 0 = 0 ==> V(1/Rf +1/Rf) = V0/Rf\n\nbut V0 = (1+Rf/R5)V\n\nV(1/R1 + 1/R2 + 1/R3 + 1/R4)\n\n= V1/R1 + V2/R2 + V3 / R3",
			"rawText": "V - V1 / R1 + V-V2/R2 + V-V3/R3 + V-0/R4 = 0\n\nV-0 / R5 + V-V0/Rf + 0 = 0 ==> V(1/Rf +1/Rf) = V0/Rf\n\nbut V0 = (1+Rf/R5)V\n\nV(1/R1 + 1/R2 + 1/R3 + 1/R4)\n\n= V1/R1 + V2/R2 + V3 / R3",
			"baseline": 216,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 2107014094,
			"isDeleted": false,
			"id": "cpJcRV82",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 575.2954545454548,
			"y": 8332.821428571431,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 476,
			"height": 149,
			"seed": 1192259726,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "##DO\n\nassume R4 = inf\nso 1/R4 = 0\n\nV(1/R1 + 1/R2 + 1/R3) = V1/R1 + V2/R2 + V3/R3",
			"rawText": "##DO\n\nassume R4 = inf\nso 1/R4 = 0\n\nV(1/R1 + 1/R2 + 1/R3) = V1/R1 + V2/R2 + V3/R3",
			"baseline": 142,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 27870158,
			"isDeleted": false,
			"id": "0pwz28yw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 594.438311688312,
			"y": 8526.250000000002,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 113,
			"height": 25,
			"seed": 1277102094,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "##Continue",
			"rawText": "##Continue",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 2111071246,
			"isDeleted": false,
			"id": "uImnxNKg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -248.46645021645008,
			"y": -907.7499999999973,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 98,
			"height": 50,
			"seed": 622239186,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Home work\n",
			"rawText": "Home work\n",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 2123212174,
			"isDeleted": false,
			"id": "6sVPlwEG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.46645021645014,
			"y": -845.7499999999973,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 476,
			"height": 149,
			"seed": 638104142,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 20,
			"fontFamily": 1,
			"text": "##DO\n\nassume R4 = inf\nso 1/R4 = 0\n\nV(1/R1 + 1/R2 + 1/R3) = V1/R1 + V2/R2 + V3/R3",
			"rawText": "##DO\n\nassume R4 = inf\nso 1/R4 = 0\n\nV(1/R1 + 1/R2 + 1/R3) = V1/R1 + V2/R2 + V3/R3",
			"baseline": 142,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 918281810,
			"isDeleted": false,
			"id": "Aa4Cro9W",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 311.5335497835499,
			"y": -855.7499999999973,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 174,
			"seed": 277879310,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 136.9230769230769,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 122,
			"textAlign": "left",
			"verticalAlign": "top"
		},
		{
			"type": "text",
			"version": 41,
			"versionNonce": 1105370066,
			"isDeleted": false,
			"id": "29s5meZi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 527.5335497835503,
			"y": -799.7499999999973,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 273,
			"height": 35,
			"seed": 1583107150,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElementIds": [],
			"fontSize": 27.999999999999964,
			"fontFamily": 1,
			"text": "9 problems of power",
			"rawText": "9 problems of power",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top"
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#a61e4d",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStrokeSharpness": "sharp",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"currentItemLinearStrokeSharpness": "round",
		"gridSize": null
	}
}
```
%%