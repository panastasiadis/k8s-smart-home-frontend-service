# Smart Home with K8s and Microservices | Streamlit GUI Application service

## Overview

This repository is part of my thesis project, "Enhancing Integration Process and Manageability of a Microservices-Based Home Automation Application with Kubernetes", and contains the front-end service built with Streamlit. It provides a user-friendly interface to manage devices, sensors, rooms, and actions. The application connects to a backend API for the application and device management and connects to InfluxDB for displaying time-series sensor data.

## Features

- **Dashboard**: Real-time monitoring of active sensors and devices.
- **Device Management**: Configure and manage devices.
- **Room Management**: Create, edit, and delete rooms.
- **Sensor Management**: Assign names and manage sensors.
- **Analytics**: View graphs and logs for sensor data.
- **Actions**: Set up automated actions based on sensor values.

## Environment Variables

- **BACKEND_URL**: URL of the backend API.
- **DOCKER_INFLUXDB_INIT_ORG**: InfluxDB organization name.
- **DOCKER_INFLUXDB_INIT_BUCKET**: InfluxDB bucket name.
- **DOCKER_INFLUXDB_INIT_ADMIN_TOKEN**: InfluxDB admin token.
- **DOCKER_INFLUXDB_HOST_TYPE**: InfluxDB host type (e.g., http).
- **DOCKER_INFLUXDB_HOST**: InfluxDB host address.
- **DOCKER_INFLUXDB_PORT**: InfluxDB port.
