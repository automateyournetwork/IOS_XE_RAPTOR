# IOS_XE_RAPTOR
An AI assistant for Cisco IOS XE that uses RAPTOR Tree Multi-Query RAG and Ollama so you can 'chat' with your Cisco IOS XE device

## Getting started

Clone the repo

Update the testbed.yaml file locally to reflect your device; it currently uses the DevNet Always On Sandbox

## Bring up the server
docker-compose up 

## Visit Ollama and download your model(s)
http://localhost:3002

Gear / settings button

Models

Download phi, mistral, llama2, gemma, etc

## Start Packet Raptor
http://localhost:8503

### Usage
This has been tested with a variety of IOS XE configurations and works best with larger data sets. For smaller devices / configurations I would recommend Packet Buddy instead.

The tool will download the Instructor-XL model dynamically, be patient, the first time you launch it, in order to provide free open source embeddings