---
title: Explicación de Journey Orchestration
description: '"Comprenda el concepto de Journey Orchestration, para qué se puede usar y los elementos clave de su funcionamiento."'
feature: Información general
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
source-git-commit: 6f3d3fcac73e5c770ae3171e2e14a22713f0d571
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 100%

---


# Explicación [!UICONTROL Journey Orchestration]

## Introducción a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] permite crear casos de uso de orquestación en tiempo real aprovechando los datos contextuales almacenados en eventos o fuentes de datos.

[!UICONTROL Journey Orchestration] es un servicio de aplicaciones integrado en Adobe Experience Platform. Proporciona un ecosistema inteligente y abierto para activar todos los datos en directo relevantes mediante una participación escalable y basada en eventos en cualquier canal que su empresa requiera, desde el marketing hasta las operaciones y el servicio. [!UICONTROL Journey Orchestration] puede aprovechar cualquier dato de Adobe Experience Platform y de cualquier sistema de envío externo para crear y ofrecer experiencias atractivas.

El siguiente vídeo presenta lo siguiente:

* El concepto de [!UICONTROL Journey Orchestration]
* Tipos de casos de uso que habilita.
* Los elementos clave de cómo [!UICONTROL Journey Orchestration] funciona.

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Cómo configurar un recorrido

Los principales pasos para preparar los recorridos de construcción son los siguientes:

1. [Configuración de eventos de flujo continuo](/help/configuring-journey-orchestration/configure-streaming-events.md): esta configuración es obligatoria, ya que [!UICONTROL Journey Orchestration] está diseñada para escuchar eventos.
1. [Configuración de Fuente de datos:](/help/configuring-journey-orchestration/configure-data-sources.md) esta configuración no es necesaria si los recorridos solo aprovechan los datos locales procedentes de una carga útil de evento.
1. [Configuración de acciones personalizadas:](/help/configuring-journey-orchestration/configure-actions.md) esto es necesario si desea utilizar un servicio de cualquier proveedor de terceros al que se pueda llamar a través de un [!DNL REST API] con una carga con formato JSON.

>[!NOTE]
>
>Estos pasos de configuración requieren conocimientos técnicos. Deberá estar familiarizado con el [Modelo de datos de Experience (XDM)](https://docs.adobe.com/content/help/es-ES/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) y [cómo componer esquemas de evento de experiencia XDM](https://docs.adobe.com/content/help/es-ES/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html).

## Cómo crear, publicar y analizar un recorrido

1. [Crear un Recorrido](/help/building-a-journey/creating-a-journey.md)
1. [Validación y publicación de un Recorrido](/help/validate-and-publish-a-journey.md)
1. [Analizar un recorrido con las herramientas de sistema de informes](/help/analyze-a-journey-via-reporting-tools.md)

## Recursos adicionales

* [Centro de ayuda de Journey Orchestration](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html)
* [Tutoriales de Adobe Experience Platform](https://docs.adobe.com/content/help/es-ES/platform-learn/tutorials/overview.html)
* [Cómo encontrar ayuda con Journey Orchestration](/help/understanding-journey-orchestration.md)
* [SDK de Adobe Experience Platform Mobile: Launch](https://docs.adobe.com/content/help/es-ES/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Servicio de ubicación de Adobe Experience Platform](https://docs.adobe.com/content/help/es-ES/places/using/home.html)
