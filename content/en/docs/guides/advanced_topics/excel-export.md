---
title: "Excel Export"
linkTitle: "Excel Export"
weight: 2
date: 2021-07-31
description: >
    <!-- 쉽고 빠르게 SpaceONE 내의 Data를 Excel로 추출하기 위한 Guide입니다. -->
    Quick and easy guide to Exporting data from SpaceONE to Excel.
---

## Overview

<!-- Excel export 기능을 이용해 손쉽게 SpaceONE내부의 데이터를 추출할 수 있습니다. -->
By using the **`Excel Export`** feature, users can easily export data within SpaceONE.

<!-- 원하는 데이터를 추출하기 위한 필터를 설정한 후, export를 누르면 바로 excel로 해당 데이터를 받을 수 있습니다.-->
Simply set up a **Filter** and select the data you'd like to extract, 

then just click the **`Export`** button. This will immediately create a Excel file for you to download.

<br/>
<br/>

## Extracting Data 
<!-- 데이터 추출하기 -->

### Step 1. Filtering the Data
<!-- Step 1. 데이터 필터링하기 -->

Move to the menu **`Iventory`** > **`Cloud Service`**.

On the top right corner, you'll be able to see the **`Excel Export`** Button.

Users can download SpaceONE's data in the form of Excel files by simply clicking this button.

You can also add filters to choose specific data to export.

![](/docs/guides/advanced_topics/excel-export-img/excel_export_01.png)

<!-- 위의 사진의 Excel 모양 버튼을 클릭하면, 원하는 데이터를 엑셀로 받을 수 있습니다. 원하는 데이터를 가공하기 위해 여러 필터를 설정할 수 있습니다. -->


<br/>

From the **`Cloud Service`** page's **Side Bar**, users can filter data by **'Service Providers', 'Service Categories',** and **'Regions'**. Users can filter through these settings and target specific data they want to export.

![](/docs/guides/advanced_topics/img/filtered_cloud_service.png)

<!-- 클라우드 서비스 페이지에서는 왼쪽 사이드 바의 필터를 이용해 각 프로바이더 별, 각 서비스 특성 별, 리전 별로 데이터를 볼 수 있고 해당 데이터를 추출할 수 있습니다.-->


<br/>

Users can also choose filters through the **`Search`** bar.

![](/docs/guides/advanced_topics/excel-export-img/excel_export_02.png)

<!-- 더 나아가, 검색창에서도 원하는 필터를 선택할 수 있습니다. -->


<br/>

Like the example image below, if you search for a specific **Project** name, you'll be given a list of all **Cloud Services** that project has.

Users can also use the **`Custom Table`** feature to combine and compose selected data into tables. Which then can be exported into Excel files. To read a more detailed guide about the **`Custom Table`** feature, click [here](/docs/guides/advanced_topics/custom-table)


![](/docs/guides/advanced_topics/excel-export-img/excel_export_03.png)

<!-- 예를 들어 이 검색 필터를 이용해 원하는 프로젝트를 검색하면, 위와 같이 프로젝트 별로 가지고 있는 클라우드 서비스를 한 눈에 볼 수 있습니다.이와 같은 방식으로 뒤의 목차에서 설명할 커스텀 테이블 기능을 활용해 원하는 데이터를 조합하여 테이블을 구성하고, 해당 데이터를 Excel로 추출할 수 있습니다. -->


<br/>
<br/>

### Step 2. Download Excel Files
<!--Step 2. Excel 다운받기-->

By clicking the **`Excel Export`** button, users can download data from the corresponding page in Excel immediately. SpaceONE currently supports this feature in the following pages : 
* Inventory > Cloud service, Server,
* Identity > Service account, User
* Plugin > Collector 

![](/docs/guides/advanced_topics/img/2021-05-10-1.15.37.png)

<!-- SpaceONE 내에서 위와 같은 Excel 모양 버튼을 클릭하면 해당하는 페이지의 데이터를 바로 excel로 받아볼 수 있습니다. 현재 Cloud service, Server, User, Service account, Collector 페이지에서 해당 기능을 지원합니다. -->


The following images are an example of a final downloaded file, exported from the Main Cloud Service page.

![](/docs/guides/advanced_topics/img/cloud_service_summary_excel.png)

<br/>

When exported from the Main Cloud Service page, the downloaded file will have a Summary on the first sheet. 

Then will have seperate sheets of detailed data for each Cloud Service. 

![](/docs/guides/advanced_topics/img/cloud_service_excel.png)

<!-- 예를 들어,Cloud service 메인 페이지에서 Export를 할 시에첫 Sheet에는 요약 정보가 들어가고 그 다음 Sheet부터는 각각의 Cloud Service에 대한 Detail 정보가 들어갑니다.-->



