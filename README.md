# Kafka Prometheus Monitoring

Kafka monitoring using prometheus, alert manager and grafana. Ansible is used as deployment tool

## Goals

* [x] Install prometheus in HA mode
* [x] Install grafana in HA mode
* [x] Install alert manager in HA mode
* [ ] Install kafka exporter
* [ ] Install jmx exporter
* [x] Config prometheus to scrap metrics from nodes
* [ ] Config prometheus to scrap metrics kafka
* [ ] Create/Customize dashboard for Kafka Broker
* [ ] Create/Customize dashboard for Zookeeper
* [ ] Create/Customize dashboard for Kafka Connect
* [ ] Create/Customize dashboard for Mirror Maker 2

## How to run

First you need to adjust your inventory. Change inventory file according to your needs. Then run

    ansible-playbook install.yaml