![GitHub license](https://img.shields.io/github/license/microsoft/IoT-For-Beginners.svg)
![GitHub contributors](https://img.shields.io/github/contributors/microsoft/IoT-For-Beginners.svg)
![GitHub issues](https://img.shields.io/github/issues/microsoft/IoT-For-Beginners.svg)
![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/IoT-For-Beginners.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/IoT-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/IoT-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/IoT-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/IoT-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/IoT-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/IoT-For-Beginners/stargazers/)

[![Español](https://img.shields.io/badge/-Spanish-blue)](translations/README.bn.md)
[![Ingles](https://img.shields.io/badge/-English-yellow)](translations/README.zh-cn.md)

# Developer Roadmap - Basic Stack

SW Sapein les comparte un** Developer Roadmap** (Hoja de ruta de desarrollador) para que cualquier desarrollador que quiera adentrarse a temas de facturación electrónica tenga una pila básica de información, lecciones, ejemplos, códigos, tecnologías, arquitecturas, entre otras herramientas para así desarrollar soluciones mantenibles y escalables.

Nuestro Developer Roadmap contiene 10 temas especificos que le ayudarán a tener una pila básica de habilidades para un desarrollador.

Muchas gracias  a nuestros autores **Heltton Ramirez** y **Octavio Hernandez**.

Agradecimientos especiales a nuestro equipo de **SW Sapien** y a nuestros revisores **.....**.

## Biografía de nuestros autores

....

**Lorem Ipsum** is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

**There are many variations** of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.

## Requerimientos necesarios

We have two choices of IoT hardware to use for the projects depending on personal preference, programming language knowledge or preferences, learning goals and availability. We have also provided a 'virtual hardware' version for those who don't have access to hardware, or want to learn more before committing to a purchase. You can read more and find a 'shopping list' on the [hardware page](./hardware.md), including links to buy complete kits from our friends at Seeed Studio.

> 💁 Find our [Code of Conduct](CODE_OF_CONDUCT.md), [Contributing](CONTRIBUTING.md), and [Translation](TRANSLATIONS.md) guidelines. We welcome your constructive feedback!

## Nuestro contenido

- Algoritmos

- Estructuras de datos

- Patrones de diseño

- Javascript

- Excercism

- Bases de datos Relacional y NoSQL

> **Nota**: Todos nuestros ejercicios, códigos de ejemplo etc., están escritos en uno o más lenguajes de programación, tecnologías y/o arquitecturas.

## Contenido

|       |              Project Name              |                       Concepts Taught                       | Learning Objectives                                                                                                                                                 |                                                        Linked Lesson                                                         |
| :---: | :------------------------------------: | :---------------------------------------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------: |
|  01   | [Getting started](./1-getting-started) |                     Introduction to IoT                     | Learn the basic principles of IoT and the basic building blocks of IoT solutions such as sensors and cloud services whilst you are setting up your first IoT device |                      [Introduction to IoT](./1-getting-started/lessons/1-introduction-to-iot/README.md)                      |
|  02   | [Getting started](./1-getting-started) |                   A deeper dive into IoT                    | Learn more about the components of an IoT system, as well as microcontrollers and single-board computers                                                            |                        [A deeper dive into IoT](./1-getting-started/lessons/2-deeper-dive/README.md)                         |
|  03   | [Getting started](./1-getting-started) | Interact with the physical world with sensors and actuators | Learn about sensors to gather data from the physical world, and actuators to send feedback, whilst you build a nightlight                                           | [Interact with the physical world with sensors and actuators](./1-getting-started/lessons/3-sensors-and-actuators/README.md) |
|  04   | [Getting started](./1-getting-started) |             Connect your device to the Internet             | Learn about how to connect an IoT device to the Internet to send and receive messages by connecting your nightlight to an MQTT broker                               |               [Connect your device to the Internet](./1-getting-started/lessons/4-connect-internet/README.md)                |
|  05   |            [Farm](./2-farm)            |                    Predict plant growth                     | Learn how to predict plant growth using temperature data captured by an IoT device                                                                                  |                          [Predict plant growth](./2-farm/lessons/1-predict-plant-growth/README.md)                           |
|  06   |            [Farm](./2-farm)            |                    Detect soil moisture                     | Learn how to detect soil moisture and calibrate a soil moisture sensor                                                                                              |                          [Detect soil moisture](./2-farm/lessons/2-detect-soil-moisture/README.md)                           |
|  07   |            [Farm](./2-farm)            |                  Automated plant watering                   | Learn how to automate and time watering using a relay and MQTT                                                                                                      |                      [Automated plant watering](./2-farm/lessons/3-automated-plant-watering/README.md)                       |
|  08   |            [Farm](./2-farm)            |               Migrate your plant to the cloud               | Learn about the cloud and cloud-hosted IoT services and how to connect your plant to one of these instead of a public MQTT broker                                   |               [Migrate your plant to the cloud](./2-farm/lessons/4-migrate-your-plant-to-the-cloud/README.md)                |
|  09   |            [Farm](./2-farm)            |         Migrate your application logic to the cloud         | Learn about how you can write application logic in the cloud that responds to IoT messages                                                                          |         [Migrate your application logic to the cloud](./2-farm/lessons/5-migrate-application-to-the-cloud/README.md)         |
|  10   |            [Farm](./2-farm)            |                   Keep your plant secure                    | Learn about security with IoT and how to keep your plant secure with keys and certificates                                                                          |                        [Keep your plant secure](./2-farm/lessons/6-keep-your-plant-secure/README.md)                         |
|  11   |       [Transport](./3-transport)       |                      Location tracking                      | Learn about GPS location tracking for IoT devices                                                                                                                   |                           [Location tracking](./3-transport/lessons/1-location-tracking/README.md)                           |
|  12   |       [Transport](./3-transport)       |                     Store location data                     | Learn how to store IoT data to be visualized or analysed later                                                                                                      |                         [Store location data](./3-transport/lessons/2-store-location-data/README.md)                         |
|  13   |       [Transport](./3-transport)       |                   Visualize location data                   | Learn about visualizing location data on a map, and how maps represent the real 3d world in 2 dimensions                                                            |                     [Visualize location data](./3-transport/lessons/3-visualize-location-data/README.md)                     |
|  14   |       [Transport](./3-transport)       |                          Geofences                          | Learn about geofences, and how they can be used to alert when vehicles in the supply chain are close to their destination                                           |                                   [Geofences](./3-transport/lessons/4-geofences/README.md)                                   |
|  15   |   [Manufacturing](./4-manufacturing)   |               Train a fruit quality detector                | Learn about training an image classifier in the cloud to detect fruit quality                                                                                       |                 [Train a fruit quality detector](./4-manufacturing/lessons/1-train-fruit-detector/README.md)                 |
|  16   |   [Manufacturing](./4-manufacturing)   |           Check fruit quality from an IoT device            | Learn about using your fruit quality detector from an IoT device                                                                                                    |           [Check fruit quality from an IoT device](./4-manufacturing/lessons/2-check-fruit-from-device/README.md)            |
|  17   |   [Manufacturing](./4-manufacturing)   |             Run your fruit detector on the edge             | Learn about running your fruit detector on an IoT device on the edge                                                                                                |             [Run your fruit detector on the edge](./4-manufacturing/lessons/3-run-fruit-detector-edge/README.md)             |
|  18   |   [Manufacturing](./4-manufacturing)   |        Trigger fruit quality detection from a sensor        | Learn about triggering fruit quality detection from a sensor                                                                                                        |        [Trigger fruit quality detection from a sensor](./4-manufacturing/lessons/4-trigger-fruit-detector/README.md)         |
|  19   |          [Retail](./5-retail)          |                   Train a stock detector                    | Learn how to use object detection to train a stock detector to count stock in a shop                                                                                |                        [Train a stock detector](./5-retail/lessons/1-train-stock-detector/README.md)                         |
|  20   |          [Retail](./5-retail)          |               Check stock from an IoT device                | Learn how to check stock from an IoT device using an object detection model                                                                                         |                     [Check stock from an IoT device](./5-retail/lessons/2-check-stock-device/README.md)                      |
|  21   |        [Consumer](./6-consumer)        |             Recognize speech with an IoT device             | Learn how to recognize speech from an IoT device to build a smart timer                                                                                             |                  [Recognize speech with an IoT device](./6-consumer/lessons/1-speech-recognition/README.md)                  |
|  22   |        [Consumer](./6-consumer)        |                     Understand language                     | Learn how to understand sentences spoken to an IoT device                                                                                                           |                        [Understand language](./6-consumer/lessons/2-language-understanding/README.md)                        |
|  23   |        [Consumer](./6-consumer)        |           Set a timer and provide spoken feedback           | Learn how to set a timer on an IoT device and give spoken feedback on when the timer is set and when it finishes                                                    |                 [Set a timer and provide spoken feedback](./6-consumer/lessons/3-spoken-feedback/README.md)                  |
|  24   |        [Consumer](./6-consumer)        |                 Support multiple languages                  | Learn how to support multiple languages, both being spoken to and the responses from your smart timer                                                               |                   [Support multiple languages](./6-consumer/lessons/4-multiple-language-support/README.md)                   |


## ¿Quieres ayudar a este grandioso proyecto?

Puedes ser contribuidor de este grandioso proyecto aportando temas de la pila básica. Para más información de como contribuir visita el siguiente enlace. ~~link~~

## Otros proyectos relacionados

Our team produces other curricula! Check out:

- [Web Dev for Beginners](https://aka.ms/webdev-beginners)
- [ML for Beginners](https://aka.ms/ml-beginners)
- [Data Science for Beginners](https://aka.ms/datascience-beginners)

## Image attributions

You can find all the attributions for the images used in this curriculum where required in the [Attributions](./attributions.md).
