---
title: Explicación del Journey Orchestration
description: Comprender el concepto de Journey Orchestration, los tipos de casos de uso que habilita y los elementos clave del funcionamiento del Journey Orchestration.
feature: Journey Orchestration
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
translation-type: tm+mt
source-git-commit: dafd8b529ec4326dd04fcf4ad766b0856cb3cfcc
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 0%

---


# Explicación [!UICONTROL Journey Orchestration]

## Introducción a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] le permite crear casos de uso de orquestación en tiempo real aprovechando los datos contextuales almacenados en eventos o fuentes de datos.

[!UICONTROL Journey Orchestration] es un servicio de aplicaciones integrado con el Adobe Experience Platform. Proporciona un ecosistema inteligente y abierto para activar todos los datos en directo relevantes mediante un compromiso escalable y basado en eventos en cualquier canal que su empresa requiera, desde el marketing hasta las operaciones y el servicio. [!UICONTROL Journey Orchestration] puede aprovechar cualquier dato del Adobe Experience Platform y de cualquier sistema de envío externo para crear y ofrecer experiencias atractivas.

El siguiente video presenta:

* El concepto de [!UICONTROL Journey Orchestration]
* Tipos de casos de uso que habilita
* Los elementos clave de cómo [!UICONTROL Journey Orchestration] funciona

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Cómo configurar un viaje

Los principales pasos para preparar los viajes de construcción son:

1. [Configurar Eventos](/help/configuring-journey-orchestration/configure-streaming-events.md) de flujo: Esta configuración es obligatoria, ya que [!UICONTROL Journey Orchestration] está diseñada para escuchar eventos.
1. [Configurar fuentes](/help/configuring-journey-orchestration/configure-data-sources.md) de datos: esta configuración no es obligatoria si sus viajes solo aprovechan los datos locales procedentes de una carga útil de evento.
1. [Configurar acciones](/help/configuring-journey-orchestration/configure-actions.md)personalizadas: Necesario si desea utilizar un servicio de cualquier proveedor de terceros al que se pueda llamar a través de un [!DNL REST API] con una carga útil con formato JSON

>[!NOTE]
>
>Estos pasos de configuración requieren conocimientos técnicos. Deberá estar familiarizado con el Modelo de datos de [experiencia (XDM)](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) y [cómo componer esquemas](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html)de evento de experiencia XDM.

## Cómo crear, publicar y analizar un viaje

1. [Crear un viaje](/help/create-a-journey.md)
1. [Validación y publicación de un viaje](/help/validate-and-publish-a-journey.md)
1. [Analizar un viaje mediante herramientas de sistema de informes](/help/analyze-a-journey-via-reporting-tools.md)

## Recursos adicionales

* [Centro de ayuda de Journey Orchestration](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Tutoriales de Adobe Experience Platform](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [Cómo encontrar ayuda con Journey Orchestration](/help/understanding-journey-orchestration.md)
* [SDK de Adobe Experience Platform Mobile: Iniciar](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Servicio de ubicación de Adobe Experience Platform](https://docs.adobe.com/content/help/en/places/using/home.html)
