---
title: "opentelemetry-collector Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the opentelemetry-collector Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-05-07 00:45:47
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/opentelemetry-collector/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/opentelemetry-collector/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/opentelemetry-collector/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/opentelemetry-collector/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | May 6th      | `sha256:150646f7d7424dbb5f8c290059ac1f919c3f663938cae2d141ff31f84c69ef59` |
|  `latest`     | May 6th      | `sha256:aea4a7dd30fc1779468181f91f3c2e608ddc4fa0f477177a4ef57d88360c70fc` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                         | Last Changed | Digest                                                                    |
|-------------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `0` `0.100.0` `latest` `0.100`                 | May 6th      | `sha256:67dd8709902690a6c1f8e62a5a82f0cc8c1c89f951d91b5f34b51cc7ea6d34bf` |
|  `0-dev` `0.100-dev` `latest-dev` `0.100.0-dev` | May 6th      | `sha256:5ac10d6b1d3a45fd588590a7449cd56908327826bb42c442bfdba8a001ca5dcf` |
|  `0.99.0-dev` `0.99-dev`                        | May 2nd      | `sha256:426134a7a289f9afe3b728103cacdb83437bb707653aada28f57fe1248380c7a` |
|  `0.99` `0.99.0`                                | May 2nd      | `sha256:fd4edcdf64de8cfda943de5887d3a77d78c9fb9eeabceb281e38b693064dffbc` |
