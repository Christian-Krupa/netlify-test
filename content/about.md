---
title: "About"
description: about desc
draft: false
type: page
menu:
  main: {}

---

about text

{{ ref . "posts/second.md" }}

{{< ref "posts/another_post.md" >}}

{{< ref "contact.md" >}}

{{ ref . "contact.md" }}

{{< relref "contact.md" >}}

[contact]({{< ref "contact.md" >}})

[second]({{< relref "posts/second.md" >}})