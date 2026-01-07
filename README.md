## What is DEATHCON 2025?

https://deathcon.io/workshops.html

https://qiita.com/hackeT/items/44b1ba8d7eec54de506e

## Welcome to "Magic of custom Visualizations with Vega, cut out for DEATH work!" workshop
Data visualization has infinite possibilities! Learn Vega to develop two beautiful custom charts making your DEATH work more vivid and implement on Kibana. Let's obtain a custom Timeline of the relationship between malicious domains and their assigned IP, and a custom Horizon for malware trends.

Youtube video: https://youtu.be/gBWPvSw62S0

## Workshop leader (Your Instructor)

**Tatsuya Hasegawa**

- X: [T_8ase](https://x.com/t_8ase)
- LinkedIn: [tatsuya-hasegawa-aa3279142](https://www.linkedin.com/in/tatsuya-hasegawa-aa3279142/)

## Target audience

- Threat Hunters
- Threat Intelligence Analysts
- Security Operations Center Analysts

## Skill levels

- Beginner
- Experienced

## Video Length

45 min planning => 51 min actually

## Work time for completion

30 ~ 60 min

## System Requirements

Participants need their PC with internet access and install docker software and [docker-elk](https://github.com/deviantony/docker-elk), OR use your own elasticsearch & kibana, OR DEATHCon's Elastic Stack instead.
Regarding docker-elk version, any version that supports Vega is fine, but for now, the instructor is using 9.2505.1.
In addition, it use Web browser software to access online Vega documents, online Vega Editor, and the Elastic's Kibana.

## Attached Vega code files

```
Vega_code
├── Vega_custom_horizon_chart.json
├── Vega_custom_horizon_chart_kibana.json
├── Vega_custom_timeline_chart.json
├── Vega_custom_timeline_chart_kibana.json
├── Vega_simplest.json
├── Vega_tutorial.json
├── fqdn_ip_array.ndjson
└── malware_trend.ndjson
```

Integrity

```
SHA2-256(Vega_custom_horizon_chart.json)= 1c31cfab56b25fec733e9ca8047f747f5d3db13cd4e38ef381d3553978147d0d
SHA2-256(Vega_custom_horizon_chart_kibana.json)= b84ec61bfd1f707a7a0e5b528d04405f5b1bee3a67c98f5072edac577a54a5de
SHA2-256(Vega_custom_timeline_chart.json)= 1c55f179a330216039c06789e0bb45842995ee8d7a925385a7113979afc7425e
SHA2-256(Vega_custom_timeline_chart_kibana.json)= 0ee9ad753d970a5d6d69befc172e72052d263e50c6588116be446d421a8fa979
SHA2-256(Vega_simplest.json)= 7d4fd05c474b34f9c6a03812ef78e0a7a1d1eff8fc6f859b3cd825d1f3e753c2
SHA2-256(Vega_tutorial.json)= 46f64937615e3586d6542431af26bde8876e2a0078f54a496800a15d12b12072
SHA2-256(fqdn_ip_array.ndjson)= 92617be7dfe96be4c5313c4cceeb76b2d8f5e8982f628e29b4db6054a4f9018a
SHA2-256(malware_trend.ndjson)= 08d52d9b4116afe89859ec1f6381040283dcd363a2e429bff89219ffb9c2b8ed
```

## Workshop Outline

### 1. Self and Workshop introduction

Video: around 00:00 - 03:20

### 2. Overview of Vega and how to debug

Video: around 03:20 - 10:24

Using:

- [Online Vega Editor](https://vega.github.io/editor/#/custom/vega)
- `Vega_simplest.json`

Reference:

- [Vega introduction](https://vega.github.io/vega/)
- [Vega official documents](https://vega.github.io/vega/docs/)

### 3. Dive into Vega tutorial

Video: around 10:24 - 16:42

Using:

- [Online Vega Editor](https://vega.github.io/editor/#/custom/vega)
- `Vega_tutorial.json`

Reference:

- [Vega tutorial](https://vega.github.io/vega/tutorials/bar-chart/)
- [Vega official documents](https://vega.github.io/vega/docs/)

### 4. Development of a custom timeline chart of domain names and assigned IP addresses

#### 4-1. Develop the timeline chart framework with the dataset embedded in the Vega code.

Video: around 16:42 - 26:52

Using:

- [Online Vega Editor](https://vega.github.io/editor/#/custom/vega)
- `Vega_custom_timeline_chart.json`

Reference:

- [Vega official documents](https://vega.github.io/vega/docs/)

#### 4-2. Modify it for the data indexed on Elasticsearch and visualize it on a Kibana

Video: around 26:52 - 36:10

Using:

- Your Elasticsearch & Kibana instance
- `fqdn_ip_array.ndjson`
- `Vega_custom_timeline_chart_kibana.json`

### 5. Development of a custom Horizon chart of malware trend

#### 5-1. Develop the horizon chart framework with the dataset embedded in the Vega code.

Video: around 36:10 - 45:13

Using:

- [Online Vega Editor](https://vega.github.io/editor/#/custom/vega)
- `Vega_custom_horizon_chart.json`

Reference:

- [Vega official documents](https://vega.github.io/vega/docs/)

#### 5-2. Modify it for the data indexed on Elasticsearch and visualize it on a Kibana

Video: around 45:13 - 50:48

Using:

- Your Elasticsearch & Kibana instance
- `malware_trend.ndjson`
- `Vega_custom_horizon_chart_kibana.json`

~ **Thank you. Happy Visualization & Hunting! Enjoy DEATHCon!** ~

# License

This workshop materials including the youtube video are managed by "CC BY-NC 4.0"（表示 - 非営利）since 2026.

    （C）2025 Tatsuya Hasegawa [hackeT Labo]
