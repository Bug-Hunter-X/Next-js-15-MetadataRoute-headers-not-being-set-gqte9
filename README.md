# Next.js 15 MetadataRoute Headers Issue

This repository demonstrates a problem encountered when using `next/server`'s `MetadataRoute` in Next.js 15 to set custom headers.  The `Cache-Control` header, specifically, doesn't seem to be applied correctly.

The `metadata.js` file contains the problematic code. The `metadataSolution.js` provides a workaround.