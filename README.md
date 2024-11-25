# Data Engineering YouTube Analysis Project

## Overview

This project focuses on securely managing, streamlining, and analyzing YouTube video data, with a particular emphasis on video categories and trending metrics.

## Project Goals
1.Data Ingestion: Develop a process to ingest data from various sources.
2.ETL Pipeline: Transform raw data into the required format for analysis.
3.Data Lake: Store data from multiple sources in a centralized repository.
4.Scalability: Ensure the system can scale to handle increasing data volumes.
5.Cloud Infrastructure: Utilize cloud services (AWS) to manage and process large datasets.
6.Reporting: Create a dashboard for visualizing and interpreting the data.

## AWS Services used
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: Identity and Access Management service to securely control access to AWS resources.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">


