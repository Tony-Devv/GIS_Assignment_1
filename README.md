<div align="center">

<span style="background:#0b3d63;color:#ffffff;padding:6px 16px;border-radius:4px;font-size:12px;font-weight:600;letter-spacing:1.4px;font-family:-apple-system,'Segoe UI',Roboto,Helvetica,Arial,sans-serif;display:inline-block;">INTRO TO MAPPING AND GIS</span>

<br><br>

# Lab Exercise #1

<hr style="border:none;border-top:2px solid #0b3d63;margin:18px 0 26px 0;">

</div>

<div align="center">

<table style="border-collapse:collapse;font-family:-apple-system,'Segoe UI',Roboto,Helvetica,Arial,sans-serif;font-size:14px;color:#111;">

<tr>
<td style="padding:6px 22px 6px 0;color:#6a737d;font-size:11px;letter-spacing:1px;text-align:right;white-space:nowrap;">STUDENT NAME</td>
<td style="padding:6px 0;font-weight:600;">Anton Zakaria Ezzat</td>
</tr>
<tr>
<td style="padding:6px 22px 6px 0;color:#6a737d;font-size:11px;letter-spacing:1px;text-align:right;white-space:nowrap;">STUDENT ID</td>
<td style="padding:6px 0;font-weight:600;">20231030</td>
</tr>
<tr>
<td style="padding:6px 22px 6px 0;color:#6a737d;font-size:11px;letter-spacing:1px;text-align:right;white-space:nowrap;">COURSE</td>
<td style="padding:6px 0;font-weight:600;">Intro to Mapping and GIS</td>
</tr>
<tr>
<td style="padding:6px 22px 6px 0;color:#6a737d;font-size:11px;letter-spacing:1px;text-align:right;white-space:nowrap;">ASSIGNMENT</td>
<td style="padding:6px 0;font-weight:600;">Lab Exercise #1</td>
</tr>
<tr>
<td style="padding:6px 22px 0 0;color:#6a737d;font-size:11px;letter-spacing:1px;text-align:right;white-space:nowrap;">DATE</td>
<td style="padding:6px 0 0;font-weight:600;">17 October 2026</td>
</tr>

</table>

</div>

<hr style="border:none;border-top:1px solid #e1e4e8;margin:26px 0 34px 0;">

## Files

| File | |
|---|---|
| `Egypt.gdb` | Geodatabase — 11 layers, EPSG:32636 |
| `Assignment1_Egypt.gpkg` | Same data as GeoPackage — [Releases](https://github.com/Tony-Devv/GIS_Assignment_1/releases/tag/v1.0) |
| `Dokki_Map_Layout.jpeg` | Q8 map — A4, 700 dpi |
| `Question_9.pdf` | Q9 map |

---

## Q1 — Geodatabase with a unified projection system (WGS1984)

`Egypt.gdb` — 11 layers, all **EPSG:32636 (WGS 84 / UTM zone 36N)**

| # | Layer | Features | | # | Layer | Features |
|---|---|---|---|---|---|---|
| 1 | Gov | 27 | | 7 | All Banks in Egypt | 687 |
| 2 | Building | 149,756 | | 8 | All_Banks_Bigger_Than_500 | 171 |
| 3 | Roads | 192,352 | | 9 | Do_Schools | 208 |
| 4 | Shykha | 5,814 | | 10 | Do_school_point | 208 |
| 5 | Landmark | 98,462 | | 11 | Assignment1_Egypt — All_Banks_In_El_Dokki | 48 |
| 6 | El_Dokki | 1 | | | | |

## Q2 — Area and location of El Dokki

| | |
|---|---|
| **Area** | 5,091,867.89 m² (Cartesian) &nbsp;·&nbsp; 5,092,183.65 m² (Ellipsoidal) |
| **Kilometres** | 5.09 km² |
| **Longitude** | 31° 12′ 25.92″ E |
| **Latitude** | 30° 02′ 36.96″ N |
| **Easting** | 327,330 m E |
| **Northing** | 3,324,840 m N |

## Q3 — Length of El Tahrir street

**7,623.535 m — 7.624 km**

## Q4 — Area of Elsaid club

**232,133.219 m² — 0.232 km²**

## Q5 — Banks in the Dokki area, with an area column

`Assignment1_Egypt — All_Banks_In_El_Dokki` — 48 features, `Area` column

## Q7 — Hotels from the Landmark layer with area > 500 m²

`All_Banks_Bigger_Than_500` — 171 features

## Q8 — Map export, JPEG at 700 dpi

![Q8](Dokki_Map_Layout.jpeg)

`Dokki_Map_Layout.jpeg` — 8,185 × 5,787 px, 700 dpi, A4 landscape, 1:35 000

## Q9 — Schools converted to points, exported as PDF

`Question_9.pdf` — A4 landscape, 1:30 000
