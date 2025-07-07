# IoT Sensor Data Analysis: Self-Supervised Learning and Anomaly Detection

This repository contains a machine learning project focused on analyzing IoT sensor data collected from a Raspberry Pi 5. The project goals are self-supervised learning techniques for automatic class identification and anomaly detection in sensor data.

## 📊 Dataset Overview

The repository contains sensor data from a Raspberry Pi 5 with the following characteristics:

- **Total Samples**: 180 samples in `data.csv`
- **Features**: 12 pre-eleborated sensor measurements (columns 0-11) plus ID
- **Data Source**: Raspberry Pi 5 sensors
- **Format**: CSV files with numerical sensor readings

### Data Structure

```
Columns 0-11: Sensor measurements (various physical parameters)
Column ID: Unique identifier for each sample
```

## 🎯 Project Objectives

### Primary Tasks

1. **Self-Supervised Learning**: Implement unsupervised learning algorithms to automatically identify patterns and classes in the sensor data without relying on predefined labels.

2. **Class Identification**: Discover natural groupings or clusters within the data that represent different operational states or conditions.

3. **Anomaly Detection**: Develop a model capable of identifying unusual patterns or outliers in the sensor data that may indicate abnormal system behavior.

## 🔍 Key Questions to Address

- What natural groupings exist in the IoT sensor data?
- Can the model identify different operational states without labels?
- What constitutes anomalous behavior in this sensor network?
- How reliable is the anomaly detection system?
- What sensor features are most important for classification?

## 📝 Notes

- The sensor data represents real IoT measurements from a Raspberry Pi 5
- The specific meaning and units of sensor measurements are not critical for the ML task
- Focus on pattern discovery and anomaly detection rather than domain-specific interpretation
- Consider computational constraints when selecting algorithms

## 🏷️ Tags

`IoT` `Machine Learning` `Self-Supervised Learning` `Anomaly Detection` `Raspberry Pi` `Sensor Data` `Unsupervised Learning` `Data Science`

---

**Last Updated**: July 2025  
