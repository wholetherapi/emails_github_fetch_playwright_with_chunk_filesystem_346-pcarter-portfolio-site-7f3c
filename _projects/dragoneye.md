---
layout: project
title: "Sparse Attention Kernels for Long-Context Decoding"
authors: "P. Carter, S. Iwasaki"
venue: "MLSys 2026"
year: 2026
status: published
project_key: dragoneye
citation: "P. Carter, S. Iwasaki. Sparse Attention Kernels for Long-Context Decoding. MLSys, 2026."
code_link: "https://github.com/wholetherapi/emails_github_fetch_playwright_with_chunk_filesystem_346-pcarter-dragoneye-kernels-7f3c"
---

Long-context decoding is limited by the cost of sparse attention. We present a family of fused kernels that combine block-sparse selection with on-the-fly memory management, targeting modern accelerator memory hierarchies. The implementation sustains near-dense throughput at a fraction of the memory footprint on contexts up to one million tokens.
