---
title: Hello HomeLab
date: 2022-05-21 12:00:00 -500
categories: [homelab, hardware]
tags: [servers,dell,hp,supermicro]     # TAG names should always be lowercase
image:
  path: /images/111.jpg
---

# Welcome

Welcome to my Homelab channel. Here, I share my personal experiences and  achievements in the realm of sustainable energy. My goal is to contribute to a world that relies more on data-driven and sustainable energy solutions, and less on fossil fuels.

In this space, I'm on a continuous learning journey, exploring and sharing insights into the ever-evolving energy industry. My focus is on understanding and utilizing data and technology to explore more efficient and environmentally friendly energy solutions. By sharing my own progress and the lessons I've learned, I hope to not only track my own growth but also to offer ideas and inspiration to others interested in renewable energy.

![Desktop View](/images/111.jpg){: width="972" height="589" }
_Hi,I am Haotian_

The content I share includes my reflections on current energy trends, my explorations into emerging renewable technologies, and the small projects I undertake to apply these technologies in practical ways. I strive to blend my growing knowledge with real-life applications, highlighting the potential of data-driven approaches in improving energy sustainability.

This channel serves as a modest gathering place for those who share a similar interest in creating a more sustainable future. Through my Homelab, I aim to foster a community of learning and sharing, where we can collectively contribute to reducing reliance on fossil fuels and moving towards a greener future, one small step at a time.

## Hardware

I use a high-performance system that's ideally suited for demanding tasks like gaming, professional software applications, and virtualization. It's powered by a 13th Gen Intel i9 processor, complemented by substantial RAM. It strikes a perfect balance between power, security, and versatility.

### Specifications


![Desktop View](/images/legion.webp){: width="972" height="589" .w-50 .right}
- **Operating System:** Microsoft Windows 11 Home, Version 10.0.22621 Build 22621.
- **System Manufacturer and Model:** Lenovo Legion Pro 7 16IRX8 (System Model: 82WR, SKU: LENOVO_MT_82WR_BU_idea_FM).
- **Processor:** 13th Gen Intel(R) Core(TM) i9-13900HX, operating at 2200 MHz with 24 cores and 32 logical processors.
- **BIOS Information:** Lenovo, Version KWCN38WW, dated 6/20/2023.
- **System Type:** x64-based PC, primarily designed for mobile use.
- **Motherboard Details:** Manufactured by Lenovo (Product: LNVNB161216, Version: SDK0T76461 WIN).
- **Memory:** 32.0 GB installed physical RAM, with 31.7 GB total physical memory available.
- **Storage and Virtual Memory:** System uses a page file located at C:\pagefile.sys with a size of 4.75 GB. The total virtual memory is 36.5 GB, with 12.7 GB available.
- **Security Features:** Includes kernel DMA protection and virtualization-based security, such as Hypervisor enforced Code Integrity.
- **Additional Features:** The system is equipped with features for virtualization and advanced security, indicating compatibility with Hyper-V and other virtualization technologies.




```javascript
console.log('hello world!');
```

```yml
name: 'Haotian MA's lab'

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - name: Check Condition A
      id: condition_a
      run: |
        # Your script to check condition A
        # If condition A is true, set some output or environment variable
        echo "conditionA=true" >> $GITHUB_ENV

    - name: Execute Step for Condition A
      if: env.conditionA == 'true'
      run: |
        # Your script for condition A

    - name: Check Condition B
      if: env.conditionA != 'true'
      id: condition_b
      run: |
        # Your script to check condition B
        # If condition B is true, set some output or environment variable
        echo "conditionB=true" >> $GITHUB_ENV

    - name: Execute Step for Condition B
      if: env.conditionB == 'true'
      run: |
        # Your script for condition B

    - name: Execute Step for Condition C
      if: env.conditionA != 'true' && env.conditionB != 'true'
      run: |
        # Your script for condition C

```bash
sudo apt update && sudo apt upgrade
```


