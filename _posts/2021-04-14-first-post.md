---
title: "SHP파일을 GeoJson으로 변환하기!"
date: 2021-12-31 09:40:28 -0400
categories: GIS 공간지도
---
준비물 : Shp 파일 및 부가 파일 (dbf, prj 등등
1. MapShaper에 접속한다
2. 파일을 import한다 (snap vertices 체크)
3. 오른쪽 위 SimpliFy 탭에서 export 할 용량을 줄일 수 있음(대신 정보가 부정확해짐)
4. 오른쪽 위 Console 탭에서 명령어 사용 가능 : -proj wgs84 로 좌표 체계 바꾸자
5. 오른쪽 위 Export 탭에서 Geojson 및 다른 포맷에 파일로 변경 가능
