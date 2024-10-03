# HHA504 Assignment: Networking in Azure and GCP

## Table of Contents
1. [Introduction](#introduction)
2. [VPC Creation in Azure](#vpc-creation-in-azure)
3. [VPC Creation in GCP](#vpc-creation-in-gcp)
4. [Assigning a Dedicated IP](#assigning-a-dedicated-ip)
5. [Mapping IP to a Domain](#mapping-ip-to-a-domain)
7. [Screenshots](#screenshots)

## Introduction
This document covers the steps taken to create Virtual Private Clouds (VPC) in both Azure and Google Cloud Platform (GCP), assign static IP addresses, and map them to domain names.

## VPC Creation in Azure
1. Navigated to the Azure portal and selected **Virtual Network (VNet)**.
2. Chose an IP address range: `10.0.0.0/16`.
3. Created a subnet: `10.0.0.0/24`.
4. Created the Virtual Network (VNet).

## VPC Creation in GCP
1. Navigated to the Google Cloud Console and created a new VPC.
2. Defined the IP range: `10.0.0.0/16`.
3. Set up a subnet: `10.0.0.0/24`.
4. Created the VPC network.

## Assigning a Dedicated IP
### In Azure:
1. Reserved a static public IP.
2. Selected **Static IP** for a Virtual Machine.
3. Associated the IP with the resource.

### In GCP:
1. Reserved a static external IP in Google Cloud Console.
2. Assigned it to a Compute Engine instance.

## Mapping IP to a Domain
### In Azure and GCP:
1. Used **Namecheap** to create a DNS zone.
2. Created an **A record** to map the domain to the static IP address for Azure.
2. Created an **A record** to point the domain to the static IP address for GCP.

## Screenshots
1. Screenshot of VPC creation in Azure.
2. Screenshot of Subnet creation in Azure
3. Screenshot of VPC creation in GCP.
4. Screenshot of IP reservation in Azure.
5. Screenshot of IP reservation in GCP.
6. Screenshot of domain mapping in Azure and GCP.
