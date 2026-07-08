# Kubernetes E-Commerce Deployment Project

## Project Overview
This project demonstrates deployment of a containerized e-commerce application on Kubernetes using AWS EC2 instances.

## Tools Used

- AWS EC2
- Docker
- Kubernetes (kubeadm)
- Jenkins
- Prometheus
- Grafana
- NGINX Ingress
- MySQL

## Project Architecture

Internet
↓
Ingress Controller
↓
Frontend
↓
Backend
↓
MySQL

Monitoring:
Prometheus → Grafana

## Features

- Kubernetes Deployment
- Services
- ConfigMaps
- Secrets
- Persistent Volumes
- Persistent Volume Claims
- Ingress Controller
- Jenkins CI/CD
- Monitoring using Prometheus & Grafana

## Kubernetes Resources

- Deployments
- Services
- ConfigMaps
- Secrets
- Persistent Volumes
- Persistent Volume Claims
- Ingress

## Monitoring

Prometheus collects metrics from Kubernetes.

Grafana visualizes:

- Node CPU
- Node Memory
- Pod Status

## Jenkins

Jenkins is deployed inside Kubernetes and exposed using NodePort.

## Repository Structure

backend/
frontend/
mysql/
ingress/
jenkins/
monitoring/
