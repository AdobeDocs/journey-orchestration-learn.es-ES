---
title: Explicación de Journey Orchestration
description: '"Comprenda el concepto de Journey Orchestration, para qué se puede usar y los elementos clave de su funcionamiento."'
feature: Overview
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
source-git-commit: a549754dd3fbffb7b45a7d66db6778bceb13ef7d
workflow-type: tm+mt
source-wordcount: '324'
ht-degree: 66%

---


# Explicación [!UICONTROL Journey Orchestration]

## Introducción a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] permite crear casos de uso de orquestación en tiempo real utilizando datos contextuales almacenados en eventos o fuentes de datos.

[!UICONTROL Journey Orchestration] es un servicio de aplicaciones integrado en Adobe Experience Platform. Proporciona un ecosistema inteligente y abierto para activar todos los datos en directo relevantes mediante una participación escalable y basada en eventos en cualquier canal que su empresa requiera, desde el marketing hasta las operaciones y el servicio. [!UICONTROL Journey Orchestration] puede utilizar cualquier dato de Adobe Experience Platform y de cualquier sistema de envío externo para crear y ofrecer experiencias atractivas.

El siguiente vídeo presenta lo siguiente:

* El concepto de [!UICONTROL Journey Orchestration]
* Tipos de casos de uso que habilita.
* Los elementos clave de cómo [!UICONTROL Journey Orchestration] funciona.

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Cómo configurar un recorrido

Los principales pasos para preparar los recorridos de construcción son los siguientes:

1. [Configuración de eventos de flujo continuo](/help/configuring-journey-orchestration/configure-streaming-events.md): esta configuración es obligatoria, ya que [!UICONTROL Journey Orchestration] está diseñada para escuchar eventos.
1. [Configuración de fuentes de datos](/help/configuring-journey-orchestration/configure-data-sources.md) : esta configuración no es necesaria si los recorridos solo utilizan datos locales procedentes de una carga útil de evento.
1. [Configuración de acciones personalizadas:](/help/configuring-journey-orchestration/configure-actions.md) esto es necesario si desea utilizar un servicio de cualquier proveedor de terceros al que se pueda llamar a través de un [!DNL REST API] con una carga con formato JSON.

>[!NOTE]
>
>Estos pasos de configuración requieren conocimientos técnicos. Debe estar familiarizado con el [Experience Data Model (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=en) y [cómo componer esquemas de eventos de experiencia XDM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=en).

## Cómo crear, publicar y analizar un recorrido

1. [Crear un Recorrido](/help/building-a-journey/creating-a-journey.md)
1. [Validación y publicación de un Recorrido](/help/validate-and-publish-a-journey.md)
1. [Analizar un recorrido con las herramientas de sistema de informes](/help/analyze-a-journey-via-reporting-tools.md)

## Recursos adicionales

* [Centro de ayuda de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es)
* [Tutoriales de Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=en)
* [Cómo encontrar ayuda con Journey Orchestration](/help/understanding-journey-orchestration.md)
* [SDK de Adobe Experience Platform Mobile: Launch](https://experienceleague.adobe.com/docs/mobile-sdk-learn/tutorials/fundamentals/understanding-the-mobile-sdks.html?lang=en)
* [Servicio de ubicación de Adobe Experience Platform](https://experienceleague.adobe.com/docs/places/using/home.html?lang=es)
