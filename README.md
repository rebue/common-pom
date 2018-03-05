# common-pom

<!-- TOC -->

- [1. 简介](#1-简介)
- [2. 结构](#2-结构)

<!-- /TOC -->

## 1. 简介

maven项目常用pom.xml文件

## 2. 结构



                            common-pom
                               │
                               │
                ┌──────────────┼──────────────┐
                │              │              │
                │              │              │
                │    common-import   rebue-import
                │
                │
      common-dependencies
              │
              │
        common-parent


                  spring-boot-starter-parent
                               │
                               │
                        sb-dependencies
                               │
                               │
                           sb-parent