# <img src="https://opensnowcat.io/favicon.ico" alt="drawing" height="22"/> OpenSnowcat </h1>

Open-Source enterprise-grade behavioral data platform. Visit our website at [opensnowcat.io](https://opensnowcat.io)

![Apache 2.0](https://img.shields.io/badge/license-Apache--2-blue.svg?style=flat)

[OpenSnowcat](https://opensnowcat.io) is an <span style="text-decoration:underline;font-weight:bold">open-source fork of Snowplow following the license changes in 2023 and early 2024</span>. We're looking to sustain an analytics platform for many businesses dependent on the rights granted by the original Apache v2.0 License.

:warning: **Questions**: Please use the [Github Discussions](https://github.com/orgs/opensnowcat/discussions/).


## Repositories
- [OpenSnowcat Enrich](https://github.com/opensnowcat/opensnowcat-enrich) [![OpenSnowcat Enrich][enrich-release-image]][enrich-releases] [![main](https://github.com/opensnowcat/opensnowcat-enrich/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/opensnowcat/opensnowcat-enrich/actions/workflows/test.yml)

- [OpenSnowcat Collector](https://github.com/opensnowcat/opensnowcat-collector) [![OpenSnowcat Enrich][collector-release-image]][collector-releases] [![main](https://github.com/opensnowcat/opensnowcat-collector/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/opensnowcat/opensnowcat-collector/actions/workflows/test.yml)

## Our Goals

- **Free and Open-Source Forever** - Provide existing and new users with a widely-accepted license that companies can trust and that won't suddenly change in the future.

- **Integrated & Cost-Efficient** - Integrate with cloud services that simplify managing the platform and running cost-efficiently and reliably at scale.

- **Stable, Compatible & Portable** - Stable over time, compatible with Snowplow and other SDKs so that existing implementation can continue to drive value and seamless portability from and to Snowplow.

## Snowplow is no longer Open-Source
On January 8th 2024 Snowplow announced it is changing its core components license to Snowplow Limited Use License Agreement (SLULA).

Effectively, everyone running Snowplow Open Source in production (we can assume all production is considered highly available) who wants to update their core Snowplow components must obtain a license from Snowplow Ltd.

## Why Snowcat is forking Snowplow

- **Free and Open** - At Snowcat Cloud, we, like many other businesses, use Snowplow Open Source in production. New and existing Snowplow users should continue to be able to run an up-to-date behavioral event data collection platform with a low operational cost.

- **Increased lock-in** - In the last few years, Snowplow has focused more on locking in users than setting them free (which is understandable). Still, we believe there's a better way: Integrate with existing, cheaper, and ever-evolving cloud services.

## Stay Informed and Get Involved

Follow OpenSnowcat on Github, participate in discussions and get involved!.


[enrich-release-image]: https://img.shields.io/github/v/release/opensnowcat/opensnowcat-enrich?link=https%3A%2F%2Fgithub.com%2Fopensnowcat%2Fopensnowcat-enrich%2Freleases
[enrich-releases]: https://github.com/opensnowcat/opensnowcat-enrich/releases

[collector-release-image]: https://img.shields.io/github/v/release/opensnowcat/opensnowcat-collector?link=https%3A%2F%2Fgithub.com%2Fopensnowcat%2Fopensnowcat-collector%2Freleases
[collector-releases]: https://github.com/opensnowcat/opensnowcat-collector/releases
