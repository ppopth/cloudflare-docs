---
order: 2
pcx-content-type: reference
---

# Cloudflare Image Resizing documentation

With Image Resizing, you can transform images on Cloudflare’s edge platform. You can resize, adjust quality, and convert images to WebP or AVIF format on demand. Cloudflare will automatically cache every derived image at the edge, so you only need to store one original image at your origin.

- Quickly and easily adapt images to your site’s layout and your visitors’ screen sizes without maintaining a server-side image processing pipeline on your servers.

- Image processing [integrates well with Workers](/image-resizing/resizing-with-workers), which enables advanced integrations such as custom URL schemes, content negotiation and responsive images based on Client Hints.

## Availability

Image Resizing is currently available for Pro, Business and Enterprise customers. To begin, ensure you have [enabled Image Resizing](/image-resizing/enable-image-resizing) in the Cloudflare dashboard.

## Two ways to use

You can use Cloudflare Image Resizing with either a pre-defined URL format or with Cloudflare Workers, for advanced use cases. 

<ButtonGroup>
  <Button type="primary" href="/image-resizing/url-format">Learn the URL format</Button>
  <Button type="secondary" href="/image-resizing/resizing-with-workers">View the Workers docs</Button>
</ButtonGroup>