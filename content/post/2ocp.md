+++
title = "Open/Closed Principle"
description = ""
categories = [
    "Development"
]
tags = [
    "development"
]
date = 2021-09-20T02:13:52Z
author = "Anon"
+++


## Introduction

This principle means you should aim to make your code open to extension but closed to modification. This is an important principle when releasing a library or framework that others will use.

For example, suppose you're maintaining a GUI framework. You could release for coders to directly modify and integrate your released code. But what happens when you release a major update four months later?

Their code will break. This will make engineers unhappy. They won't want to use your library for much longer, no matter how helpful it may be.

Instead, release code that prevents direct modification and encourages extension. This separates core behavior from modified behavior. The code is more stable and easier to maintain. 
