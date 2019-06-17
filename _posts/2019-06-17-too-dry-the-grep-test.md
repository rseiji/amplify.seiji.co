---
title: Too DRY - The Grep Test
date: 2019-06-17 03:00:00 +0000
source: http://jamie-wong.com/2013/07/12/grep-test/
tags: []

---
Jamie Wong's definition:

> The Grep Test: If any code declares or makes use of a function, class, module, or variable that cannot be located by grepping for its full identifying token, it fails the Grep Test.

Mostly issues caused by code generation. Try to make the token searchable, if not by code, by comments at least.