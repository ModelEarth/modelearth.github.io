# ModelEarth Repositories

[Earthscape chat dev](https://github.com/Earthscape/chat) - Our NextJS Vercel deployment parent repo. <!-- ananthpai1998 -->

[ModelEarth chat fork](https://github.com/ModelEarth/chat) - For chat trained with our model.earth repos.

[codechat-vectors](/codechat-vectors) - Pinecone Vectors trained with [modelearth repos](https://github.com/modelearth/) listed below.

## Model.earth Repos

Our webroot repo loads these submodules, plus claude.md and [vector_sync.yml](https://github.com/ModelEarth/webroot/blob/main/.github/workflows/vector_sync.yml) - [Get Started](https://model.earth/webroot/)

| Name | Repository | Description |
|------|------------|-------------|
| [webroot](https://model.earth/webroot/) | [github.com/modelearth/webroot](https://github.com/modelearth/webroot) | PartnerTools webroot |
| [cloud](../cloud/) | [github.com/modelearth/cloud](https://github.com/modelearth/cloud) | Flask for python colabs |
| [chat](../chat/) | [github.com/modelearth/chat](https://github.com/modelearth/chat) | Chat UX |
| [codechat-vectors](../codechat-vectors/) | [github.com/modelearth/codechat-vectors](https://github.com/modelearth/codechat-vectors) | Chat RAG using Pinecone |
| [comparison](../comparison/) | [github.com/modelearth/comparison](https://github.com/modelearth/comparison) | Trade Flow data visualizations |
| [exiobase](../exiobase/) | [github.com/modelearth/comparison](https://github.com/modelearth/exiobase) | Trade data to CSV and SQL |
| [feed](../feed/) | [github.com/modelearth/feed](https://github.com/modelearth/feed) | FeedPlayer video/gallery |
| [home](../home/) | [github.com/modelearth/home](https://github.com/modelearth/home) | Everybody's Home Page |
| [io](../io/) | [github.com/modelearth/io](https://github.com/modelearth/io) | React Input-Output widgets for states |
| [localsite](../localsite/) | [github.com/modelearth/localsite](https://github.com/modelearth/localsite) | Core javacript utilities, tabulator |
| [products](../products/) | [github.com/modelearth/products](https://github.com/modelearth/products) | Building Transparency Product API |
| [profile](../profile/) | [github.com/modelearth/profile](https://github.com/modelearth/profile) | Footprint Reports for communities and industries |
| [projects](../projects/) | [github.com/modelearth/projects](https://github.com/modelearth/projects) | Overview and TODOs - Projects Hub |
| [realitystream](../realitystream/) | [github.com/modelearth/realitystream](https://github.com/modelearth/realitystream) | Run Models colab |
| [reports](../reports/) | [github.com/modelearth/realitystream](https://github.com/modelearth/reports) | Output from RealityStream colab |
| [swiper](../swiper/) | [github.com/modelearth/swiper](https://github.com/modelearth/swiper) | UI swiper component for FeedPlayer |
| [team](../team/) | [github.com/modelearth/team](https://github.com/modelearth/team) | Rust API for Azure and AI Insights |  
| [community-forecasting](../community-forecasting/) | [github.com/modelearth/community-forecasting](https://github.com/modelearth/community-forecasting) | Javascript ML with maps (2018) |

<br>Optional:

**Extra repos:** (forked and cloned into webroot) topojson, community, nisar, useeio-json, trade-data

**Inactive repos:** planet, earthscape

## Data-Pipeline (static csv and json output for fast web reports)

These output repos may be pulled into local webroots during data processing, but we avoid committing these as a submodules in the webroots due to their large size. The static data in these repos is pulled directly through Github Pages and the Cloudflare CDN.

| Name | Repository | Description |
|------|------------|-------------|
| [data-pipeline](../data-pipeline/) | [github.com/modelearth/data-pipeline](https://github.com/modelearth/data-pipeline) | Python data processing pipeline |
| [trade-data](../trade-data/) | [github.com/modelearth/trade-data](https://github.com/modelearth/trade-data) | Tradeflow data outputs |
| [products-data](../products-data/) | [github.com/modelearth/products-data](https://github.com/modelearth/products-data) | Product impact profiles |
| [community-data](../community-data/) | [github.com/modelearth/community-data](https://github.com/modelearth/community-data) | Community-level data outputs |
| [community-timelines](../community-timelines/) | [github.com/modelearth/community-timelines](https://github.com/modelearth/community-timelines) | Timeline data for communities |
| [community-zipcodes](../community-zipcodes/) | [github.com/modelearth/community-zipcodes](https://github.com/modelearth/community-zipcodes) | ZIP code level community data |


