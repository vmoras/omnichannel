# Deploy FastAPI on Render

Use this repo as a template to deploy a Python [FastAPI](https://fastapi.tiangolo.com) service on Render.

See https://render.com/docs/deploy-fastapi or follow the steps below:

## Manual Steps

1. You may use this repository directly or [create your own repository from this template](https://github.com/render-examples/fastapi/generate) if you'd like to customize the code.
2. Create a new Web Service on Render.
3. Specify the URL to your new repository or this repository.
4. Render will automatically detect that you are deploying a Python service and use `pip` to download the dependencies.
5. Specify the following as the Start Command.

    ```shell
    uvicorn main:app --host 0.0.0.0 --port $PORT
    ```

6. Click Create Web Service.

Or simply click:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/render-examples/fastapi)

## Thanks

Thanks to [Harish](https://harishgarg.com) for the [inspiration to create a FastAPI quickstart for Render](https://twitter.com/harishkgarg/status/1435084018677010434) and for some sample code!


# Ventanilla Única (Omnicalidad) - Plataforma de Vigilancia de Servicios Domiciliarios

Este repositorio contiene el desarrollo de una plataforma web para la gestión y vigilancia de quejas sobre empresas prestadoras de servicios domiciliarios como Energía, Agua, Alcantarillado y Aseo.

## Descripción del Proyecto

El objetivo principal de la plataforma es recibir las quejas de los ciudadanos sobre la prestación de los servicios domiciliarios a través de diferentes canales, unificarlas cuando sea necesario, clasificarlas y enrutar cada una a la empresa correspondiente según los criterios previamente definidos.

### Características Principales:
- Recepción de quejas desde múltiples fuentes.
- Unificación y tipificación de las quejas.
- Enrutamiento automático a las empresas prestadoras de servicios.
- Control y vigilancia de los tiempos de respuesta.
- Sistema de semáforo para identificar quejas próximas a vencer y vencidas.
- Generación automática de notificaciones de incumplimiento.
- Asignación equitativa de casos a profesionales responsables.

## Estado del Proyecto

⚠️ **Este proyecto aún está en desarrollo y no está finalizado.** ⚠️

Las funcionalidades descritas están en proceso de implementación y pueden estar sujetas a cambios.
