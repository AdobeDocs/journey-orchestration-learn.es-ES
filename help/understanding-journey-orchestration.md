---
title: Explicación de Journey Orchestration
description: Comprenda el concepto de Journey Orchestration, para qué se puede usar y los elementos clave de su funcionamiento.
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: tm+mt
source-wordcount: '325'
ht-degree: 99%

---

# Explicación [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] permite crear casos de uso de orquestación en tiempo real aprovechando los datos contextuales almacenados en eventos o fuentes de datos.

## Introducción a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] es un servicio de aplicaciones integrado en Adobe Experience Platform. Proporciona un ecosistema inteligente y abierto para activar todos los datos en directo relevantes mediante una participación escalable y basada en eventos en cualquier canal que su empresa requiera, desde el marketing hasta las operaciones y el servicio. [!UICONTROL Journey Orchestration] puede aprovechar cualquier dato de Adobe Experience Platform y de cualquier sistema de envío externo para crear y ofrecer experiencias atractivas.

El siguiente vídeo presenta lo siguiente:

* El concepto de [!UICONTROL Journey Orchestration]
* Tipos de casos de uso que habilita.
* Los elementos clave de cómo [!UICONTROL Journey Orchestration] funciona.

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## Cómo configurar un recorrido

Los principales pasos para preparar los recorridos de construcción son los siguientes:

1. [Configuración de eventos de flujo continuo](/help/configuring-journey-orchestration/configure-streaming-events.md): esta configuración es obligatoria, ya que [!UICONTROL Journey Orchestration] está diseñada para escuchar eventos.
1. [Configuración de fuentes de datos](/help/configuring-journey-orchestration/configure-data-sources.md): esta configuración no es necesaria si los recorridos solo aprovechan los datos locales procedentes de una carga útil de evento.
1. [Configuración de acciones personalizadas](/help/configuring-journey-orchestration/configure-actions.md): esto es necesario si desea utilizar un servicio de cualquier proveedor de terceros al que se pueda llamar a través de una [!DNL REST API] con una carga útil con formato JSON.

>[!NOTE]
>
>Estos pasos de configuración requieren conocimientos técnicos. Deberá estar familiarizado con el [Modelo de datos de Experience (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=es) y [cómo componer esquemas de evento de experiencia XDM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=es).

## Cómo crear, publicar y analizar un recorrido

1. [Creación de un recorrido](/help/building-a-journey/creating-a-journey.md)
1. [Validación y publicación de un recorrido](/help/validate-and-publish-a-journey.md)
1. [Análisis de un recorrido con las herramientas de creación de informes](/help/analyze-a-journey-via-reporting-tools.md)

## Recursos adicionales

* [Centro de ayuda de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es)
* [Tutoriales de Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=es)
* [Cómo encontrar ayuda con Journey Orchestration](/help/understanding-journey-orchestration.md)
* [SDK de Adobe Experience Platform Mobile: Launch](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=es)
* [Servicio de ubicación de Adobe Experience Platform](https://experienceleague.adobe.com/docs/places/using/home.html?lang=es)
