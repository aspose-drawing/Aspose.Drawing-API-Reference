---
title: HatchStyle
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan pola berbeda yang tersedia untuk objek.
type: docs
weight: 27
url: /id/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Menentukan pola berbeda yang tersedia untuk objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Horizontal](#Horizontal) | Pola garis horizontal. |
| [Vertical](#Vertical) | Pola garis vertikal. |
| [ForwardDiagonal](#ForwardDiagonal) | Pola garis pada diagonal dari kiri atas ke kanan bawah. |
| [BackwardDiagonal](#BackwardDiagonal) | Pola garis pada diagonal dari kanan atas ke kiri bawah. |
| [Cross](#Cross) | Menentukan garis horizontal dan vertikal yang saling bersilangan. |
| [DiagonalCross](#DiagonalCross) | Pola garis diagonal bersilangan. |
| [Percent05](#Percent05) | Menentukan pola hatch 5 persen. |
| [Percent10](#Percent10) | Menentukan pola hatch 10 persen. |
| [Percent20](#Percent20) | Menentukan pola hatch 20 persen. |
| [Percent25](#Percent25) | Menentukan pola hatch 25 persen. |
| [Percent30](#Percent30) | Menentukan pola hatch 30 persen. |
| [Percent40](#Percent40) | Menentukan pola hatch 40 persen. |
| [Percent50](#Percent50) | Menentukan pola hatch 50 persen. |
| [Percent60](#Percent60) | Menentukan pola hatch 60 persen. |
| [Percent70](#Percent70) | Menentukan pola hatch 70 persen. |
| [Percent75](#Percent75) | Menentukan pola hatch 75 persen. |
| [Percent80](#Percent80) | Menentukan pola hatch 80 persen. |
| [Percent90](#Percent90) | Menentukan pola hatch 90 persen. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Menentukan garis diagonal yang miring ke kanan dari titik atas ke titik bawah dan berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, tetapi tidak di-antialias. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Menentukan garis diagonal yang miring ke kiri dari titik atas ke titik bawah dan berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, tetapi tidak di-antialias. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Menentukan garis diagonal yang miring ke kanan dari titik atas ke titik bawah, berjarak 50 persen lebih dekat daripada, dan memiliki lebar dua kali lipat `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Menentukan garis diagonal yang miring ke kiri dari titik atas ke titik bawah, berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, dan memiliki lebar dua kali lipatnya, tetapi garis tidak di-antialias. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Menentukan garis diagonal yang miring ke kanan dari titik atas ke titik bawah, memiliki jarak yang sama dengan gaya hatch `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, dan tiga kali lebarannya, tetapi tidak di-antialias. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Menentukan garis diagonal yang miring ke kiri dari titik atas ke titik bawah, memiliki jarak yang sama dengan gaya hatch `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, dan tiga kali lebarannya, tetapi tidak di-antialias. |
| [LightVertical](#LightVertical) | Menentukan garis vertikal yang berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | Menentukan garis horizontal yang berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | Menentukan garis vertikal yang berjarak 75 persen lebih dekat daripada gaya hatch `System.Drawing.drawing2d.HatchStyle.Vertical` (atau 25 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | Menentukan garis horizontal yang jaraknya 75 persen lebih dekat dibandingkan gaya hatch `System.Drawing.drawing2d.HatchStyle.Horizontal` (atau 25 persen lebih dekat dibandingkan `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | Menentukan garis vertikal yang jaraknya 50 persen lebih dekat dibandingkan `System.Drawing.drawing2d.HatchStyle.Vertical` dan memiliki lebar dua kali lipatnya. |
| [DarkHorizontal](#DarkHorizontal) | Menentukan garis horizontal yang jaraknya 50 persen lebih dekat dibandingkan `System.Drawing.drawing2d.HatchStyle.Horizontal` dan memiliki lebar dua kali lebar `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Menentukan garis diagonal bergaris putus-putus, yang miring ke kanan dari titik atas ke titik bawah. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Menentukan garis diagonal bergaris putus-putus, yang miring ke kiri dari titik atas ke titik bawah. |
| [DashedHorizontal](#DashedHorizontal) | Menentukan garis horizontal bergaris putus-putus. |
| [DashedVertical](#DashedVertical) | Menentukan garis vertikal bergaris putus-putus. |
| [SmallConfetti](#SmallConfetti) | Menentukan hatch yang memiliki tampilan confetti. |
| [LargeConfetti](#LargeConfetti) | Menentukan hatch yang memiliki tampilan confetti, dan terdiri dari potongan yang lebih besar dibandingkan `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | Menentukan garis horizontal yang terdiri dari zigzag. |
| [Wave](#Wave) | Menentukan garis horizontal yang terdiri dari tilde. |
| [DiagonalBrick](#DiagonalBrick) | Menentukan hatch yang memiliki tampilan bata berlapis yang miring ke kiri dari titik atas ke titik bawah. |
| [HorizontalBrick](#HorizontalBrick) | Menentukan hatch yang memiliki tampilan bata berlapis secara horizontal. |
| [Weave](#Weave) | Menentukan hatch yang memiliki tampilan bahan anyaman. |
| [Plaid](#Plaid) | Menentukan hatch yang memiliki tampilan bahan kotak-kotak. |
| [Divot](#Divot) | Menentukan hatch yang memiliki tampilan cekungan. |
| [DottedGrid](#DottedGrid) | Menentukan garis horizontal dan vertikal, masing-masing terdiri dari titik-titik, yang saling bersilangan. |
| [DottedDiamond](#DottedDiamond) | Menentukan garis diagonal maju dan diagonal mundur, masing-masing terdiri dari titik-titik, yang saling bersilangan. |
| [Shingle](#Shingle) | Menentukan hatch yang memiliki tampilan sirap berlapis diagonal yang miring ke kanan dari titik atas ke titik bawah. |
| [Trellis](#Trellis) | Menentukan hatch yang memiliki tampilan teralis. |
| [Sphere](#Sphere) | Menentukan hatch yang memiliki tampilan bola-bola yang bersebelahan satu sama lain. |
| [SmallGrid](#SmallGrid) | Menentukan garis horizontal dan vertikal yang bersilangan dan jaraknya 50 persen lebih dekat dibandingkan gaya hatch `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Menentukan hatch yang memiliki tampilan papan catur. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Menentukan hatch yang memiliki tampilan papan catur dengan kotak yang berukuran dua kali lipat dibandingkan `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | Menentukan garis diagonal maju dan diagonal mundur yang bersilangan tetapi tidak anti-alias. |
| [SolidDiamond](#SolidDiamond) | Menentukan pola hatch yang tampak seperti papan catur yang ditempatkan secara diagonal. |
| [LargeGrid](#LargeGrid) | Menentukan gaya hatch `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | Menentukan gaya hatch `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | Menentukan gaya hatch `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Pola garis horizontal.

### Vertical {#Vertical}
```
public static final int Vertical
```


Pola garis vertikal.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Pola garis pada diagonal dari kiri atas ke kanan bawah.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Pola garis pada diagonal dari kanan atas ke kiri bawah.

### Cross {#Cross}
```
public static final int Cross
```


Menentukan garis horizontal dan vertikal yang saling bersilangan.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Pola garis diagonal bersilangan.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Menentukan hatch 5 persen. Rasio warna latar depan ke warna latar belakang adalah 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Menentukan hatch 10 persen. Rasio warna latar depan ke warna latar belakang adalah 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Menentukan hatch 20 persen. Rasio warna latar depan ke warna latar belakang adalah 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Menentukan hatch 25 persen. Rasio warna latar depan ke warna latar belakang adalah 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Menentukan hatch 30 persen. Rasio warna latar depan ke warna latar belakang adalah 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Menentukan hatch 40 persen. Rasio warna latar depan ke warna latar belakang adalah 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Menentukan hatch 50 persen. Rasio warna latar depan ke warna latar belakang adalah 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Menentukan hatch 60 persen. Rasio warna latar depan ke warna latar belakang adalah 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Menentukan hatch 70 persen. Rasio warna latar depan ke warna latar belakang adalah 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Menentukan hatch 75 persen. Rasio warna latar depan ke warna latar belakang adalah 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Menentukan hatch 80 persen. Rasio warna latar depan ke warna latar belakang adalah 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Menentukan hatch 90 persen. Rasio warna latar depan ke warna latar belakang adalah 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Menentukan garis diagonal yang miring ke kanan dari titik atas ke titik bawah dan berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, tetapi tidak di-antialias.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Menentukan garis diagonal yang miring ke kiri dari titik atas ke titik bawah dan berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, tetapi tidak di-antialias.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Menentukan garis diagonal yang miring ke kanan dari titik atas ke titik bawah, berjarak 50 persen lebih dekat, dan lebar dua kali lipat dari `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. Pola hatch ini tidak anti-aliased.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Menentukan garis diagonal yang miring ke kiri dari titik atas ke titik bawah, berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, dan memiliki lebar dua kali lipatnya, tetapi garis tidak di-antialias.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Menentukan garis diagonal yang miring ke kanan dari titik atas ke titik bawah, memiliki jarak yang sama dengan gaya hatch `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`, dan tiga kali lebarannya, tetapi tidak di-antialias.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Menentukan garis diagonal yang miring ke kiri dari titik atas ke titik bawah, memiliki jarak yang sama dengan gaya hatch `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`, dan tiga kali lebarannya, tetapi tidak di-antialias.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Menentukan garis vertikal yang berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Menentukan garis horizontal yang berjarak 50 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Menentukan garis vertikal yang berjarak 75 persen lebih dekat daripada gaya hatch `System.Drawing.drawing2d.HatchStyle.Vertical` (atau 25 persen lebih dekat daripada `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Menentukan garis horizontal yang jaraknya 75 persen lebih dekat dibandingkan gaya hatch `System.Drawing.drawing2d.HatchStyle.Horizontal` (atau 25 persen lebih dekat dibandingkan `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Menentukan garis vertikal yang jaraknya 50 persen lebih dekat dibandingkan `System.Drawing.drawing2d.HatchStyle.Vertical` dan memiliki lebar dua kali lipatnya.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Menentukan garis horizontal yang jaraknya 50 persen lebih dekat dibandingkan `System.Drawing.drawing2d.HatchStyle.Horizontal` dan memiliki lebar dua kali lebar `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Menentukan garis diagonal bergaris putus-putus, yang miring ke kanan dari titik atas ke titik bawah.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Menentukan garis diagonal bergaris putus-putus, yang miring ke kiri dari titik atas ke titik bawah.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Menentukan garis horizontal bergaris putus-putus.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Menentukan garis vertikal bergaris putus-putus.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Menentukan hatch yang memiliki tampilan confetti.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Menentukan hatch yang memiliki tampilan confetti, dan terdiri dari potongan yang lebih besar dibandingkan `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Menentukan garis horizontal yang terdiri dari zigzag.

### Wave {#Wave}
```
public static final int Wave
```


Menentukan garis horizontal yang terdiri dari tilde.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Menentukan hatch yang memiliki tampilan bata berlapis yang miring ke kiri dari titik atas ke titik bawah.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Menentukan hatch yang memiliki tampilan bata berlapis secara horizontal.

### Weave {#Weave}
```
public static final int Weave
```


Menentukan hatch yang memiliki tampilan bahan anyaman.

### Plaid {#Plaid}
```
public static final int Plaid
```


Menentukan hatch yang memiliki tampilan bahan kotak-kotak.

### Divot {#Divot}
```
public static final int Divot
```


Menentukan hatch yang memiliki tampilan cekungan.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Menentukan garis horizontal dan vertikal, masing-masing terdiri dari titik-titik, yang saling bersilangan.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Menentukan garis diagonal maju dan diagonal mundur, masing-masing terdiri dari titik-titik, yang saling bersilangan.

### Shingle {#Shingle}
```
public static final int Shingle
```


Menentukan hatch yang memiliki tampilan sirap berlapis diagonal yang miring ke kanan dari titik atas ke titik bawah.

### Trellis {#Trellis}
```
public static final int Trellis
```


Menentukan hatch yang memiliki tampilan teralis.

### Sphere {#Sphere}
```
public static final int Sphere
```


Menentukan hatch yang memiliki tampilan bola-bola yang bersebelahan satu sama lain.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Menentukan garis horizontal dan vertikal yang bersilangan dan jaraknya 50 persen lebih dekat dibandingkan gaya hatch `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Menentukan hatch yang memiliki tampilan papan catur.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Menentukan hatch yang memiliki tampilan papan catur dengan kotak yang berukuran dua kali lipat dibandingkan `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Menentukan garis diagonal maju dan diagonal mundur yang bersilangan tetapi tidak anti-alias.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Menentukan pola hatch yang tampak seperti papan catur yang ditempatkan secara diagonal.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Menentukan gaya hatch `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


Menentukan gaya hatch `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


Menentukan gaya hatch `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

