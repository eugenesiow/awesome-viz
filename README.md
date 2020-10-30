# Awesome Viz-Stack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/eugenesiow/awesome-viz)

A curated list of amazing awesome Viz-Stack resources.

See also: [awesome-research](https://gitly.hopto.org/eugene/awesome-research), [DSO Viz Toolkit](https://gitly.hopto.org/eugene/dso-viz).

## 📖 Table of Contents

 - [Declarative](#-declarative)
 - [Data Analytics](#-data-analytics)
 - [VueJS](#-vuejs)
 - [CSS](#-css)
 - [Graph](#-graph)
 - [Geospatial](#-geospatial)
 - [HCI](#-hci)
 - [Trend](#-trend-visualisation)
 - [Collaborative](#-collaborative)
 - [Cross Filtering](#-cross-filtering) 
 - [Graphics and Animation](#-graphics-animation) 
 - [Databases](#databases)
   - [Graph Databases](#-graph-databases)
 - [Datasets](#datasets)
   - [Graph Datasets](#-graph-datasets)
 - [Papers](#papers)
   - [Graph Papers](#-graph-papers)
 - [Articles](#-articles)
 - More *Awesomeness*
    - [Awesome Research](https://gitly.hopto.org/eugene/awesome-research)
    - [Awesome Sense Making](https://gitly.hopto.org/eugene/awesome-sense-making)
    - [Awesome Engineering](https://gitly.hopto.org/eugene/awesome-engineering)

## [↑](#contents) Declarative

*Tools, frameworks, libraries to build declarative visualisations.*

* [NL4DV](https://github.com/nl4dv/nl4dv) - Natural Language toolkit for Data Visualization. It takes a natural language query about a given dataset as input and outputs a structured JSON object containing: (1) Data attributes, (2) Analytic tasks, and (3) Visualizations (Vega-Lite specifications). The [showcase](https://nl4dv.github.io/nl4dv/showcase.html) shows example use cases and applications. [Presented](https://youtu.be/U5uDyILweu8) at IEEE VIS 2020. (Also No Code)
* [Vega](https://vega.github.io/vega/) - A visualization grammar, a declarative language for creating, saving, and sharing interactive visualization designs. With Vega, you can describe the visual appearance and interactive behavior of a visualization in a JSON format, and generate web-based views using Canvas or SVG.
* [encodable](https://github.com/kristw/encodable) - When you have a visualization component, this library helps you defines the visual channels that you can encode data into and provide API similar to vega-lite's grammar for consumers to customize the visual encoding.
* [P4](https://github.com/jpkli/p4) - P4 is JavaScript library for accelerating data processing and visualization using the GPU. P4 provides an intuitive and declarative API for specifying common data transformations and visualizations, which automatically compile to WebGL shader programs for parallel computing. For data processing, P4 is more than 10X faster than codes based on JavaScript Array functions. For visualizing large data, P4 is at least 10X faster than Canvas, and 20X faster than SVG.
* [P6](https://github.com/jpkli/p6) - P6 is a research project for developing a declarative language to specify visual analytics processes that integrate machine learning methods with interactive visualization for data analysis and exploration. P6 uses P4 for GPU accelerated data processing and rendering, and leverages Scikit-Learn and other Python libraries for supporting machine learning algorithms.
* [Kyrix-S](https://github.com/tracyhenry/kyrix) - Kyrix facilitates the creation of data visualizations with details-on-demand interactions (e.g. pan and zoom, see the demo gallery1 above). In visualizations of such, the underlying dataset is often large. To deal with large data, Kyrix is focused on optimizing two goals: 1) usable declarative API library for visualization developers and 2) 500ms response time to user interactions, which is required to enable interactive browsing.

## [↑](#contents) Data Analytics

*Tools, frameworks, libraries for data analytics and machine learning visualisations.*

* [DruidJS](https://github.com/saehm/DruidJS) - DruidJS is a JavaScript library for dimensionality reduction. With dimesionality reduction you can project high-dimensional data to a lower dimensionality while keeping method-specific properties of the data. DruidJS makes it easy to project a dataset with the implemented dimensionality reduction methods.
* [PipelineProfiler](https://github.com/VIDA-NYU/PipelineVis) - AutoML Pipeline exploration tool compatible with Jupyter Notebooks. Supports auto-sklearn and D3M pipeline format.

## [↑](#contents) VueJS

*A front-end Javascript for the Web which allows reactive components and design. It's fast, elegant and easy-to-learn.*

* [VueJS](https://vuejs.org/) - The progressive Javascript framework.
* [Quasar Framework](https://quasar.dev/) - An Open Source set of UI components for VueJS.
* [Vuex](https://vuex.vuejs.org/) - Vuex is a state management pattern + library for Vue.js applications.
* [Vue + WebAssembly](https://medium.com/@brockreece/vue-webassembly-1a09e38d0389) - A medium article which outlines a means of integrating Web Assembly functions into every component of a Vue-cli generated Webpack project.

## [↑](#contents) CSS

*Innovations on the CSS front.*

* [--var hack](https://lea.verou.me/2020/10/the-var-space-hack-to-toggle-multiple-values-with-one-custom-property/) - The -​-var: ; hack to toggle multiple values with one custom property.


## [↑](#contents) Graph

*Graph visualisation libraries for the web.*

* [Cytoscape.js](https://js.cytoscape.org/) - Graph theory (network) library for visualisation and analysis.
* [Stardust.js](https://stardustjs.github.io/examples/graph/) - Stardust is a library for rendering information visualizations with GPU (WebGL).
* [vizceral](https://github.com/Netflix/vizceral) - Netflix's WebGL visualization for displaying animated traffic graphs.
* [Andrei Kashcha](https://github.com/anvaka)
  * [Software Galaxies](https://github.com/anvaka/pm) - Beautiful interactive viz of software repository galaxies.
  * [ngraph.graph](https://github.com/anvaka/ngraph.graph) - Graph data structure for ngraph.*.
  * [VivaGraphJS](https://github.com/anvaka/VivaGraphJS) - Graph drawing library for JavaScript.

## [↑](#contents) Geospatial

*Geospatial visualisation libraries for the web.*

* [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/api/) - Mapbox GL JS is a JavaScript library that uses WebGL to render interactive maps from vector tiles and Mapbox styles. 
* [Klokan Technologies](https://www.klokantech.com/products/) - Lots of Open Source mapping products.
* [Cesium.js](https://cesium.com/cesiumjs/) - CesiumJS is an open source JavaScript library for creating 3D globes and maps.
* [Vis.gl](https://vis.gl/) - Uber Visualization’s open-source frameworks.

## [↑](#contents) HCI

*Human computer interaction focused visualisation libraries.*

* [Piling.js](https://piling.js.org/) - A JavaScript Library for Interactive Visual Piling of Small Multiples. [Presented](https://www.youtube.com/watch?v=-SlwWtTCWFU) at VIS 2020. Best [Paper](https://vcg.seas.harvard.edu/publications/a-generic-framework-and-library-for-exploration-of-small-multiples-through-interactive-piling) Honourable Mention for IEEE InfoVis.

## [↑](#contents) Trend Visualisation

*Visually explore, understand, and present trend data.*

* [SandDance](https://github.com/Microsoft/SandDance) - SandDance uses unit visualizations, which apply a one-to-one mapping between rows in your database and marks on the screen. Smooth animated transitions between views help you to maintain context as you interact with your data.
* [Perspective](https://github.com/Microsoft/SandDance) - Streaming Analytics via WebAssembly, Perspective is an interactive visualization component for large, real-time datasets.

## [↑](#contents) Collaborative

*Frameworks for collaborative editing and visualisation on the web.*

* [VisConnect](https://github.com/michaschwab/VisConnect) - Live collaboration for web based visualizations. Events, such as clicking, are synchronized across collaborators.
* [Webstrates](https://github.com/Webstrates/Webstrates) - Webstrates is a research prototype enabling collaborative editing of websites through DOM manipulations.
* [ShareDB](https://github.com/share/sharedb) - Realtime database backend based on Operational Transformation (OT).

## [↑](#contents) Cross Filtering

*Cross-filtering visualisation libraries for the web.*

* [dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js. 
* [Crossfilter](http://crossfilter.github.io/crossfilter/) - Crossfilter is a JavaScript library for exploring large multivariate datasets in the browser.
* [Reductio](https://github.com/crossfilter/reductio) - Reductio is a library for generating Crossfilter reduce functions and applying them to Crossfilter groups.
* [Universe](https://crossfilter.github.io/universe/) - Query and explore multivariate datasets.
* [MapD Charting](https://github.com/omnisci/mapd-charting) - Dimensional charting built to work natively with crossfilter rendered using d3.js.

## [↑](#contents) Graphics / Animation

*Graphics and animation libraries.*

* [Manim](https://github.com/3b1b/manim) - Manim is an animation engine for explanatory math videos. It's used to create precise animations programmatically.

## [↑](#contents) Graph Databases

*Graph databases are workload-specific database management systems that prioritise the storage of graph nodes, edges and their properties.*

* [RedisGraph](https://oss.redislabs.com/redisgraph/) - Fast graph processing powered by linear algebra and matrix multiplication. Implemented as a Redis module. 

## [↑](#contents) Graph Datasets

*Large graph datasets (and tools obtaining large datasets) for visualisation and experimentation.*

* [SNAP](http://snap.stanford.edu/data/index.html) - Stanford Large Network Dataset Collection by SNAP (Stanford Network Analysis Project).
* [Open Academic Graph](https://www.openacademic.ai/oag/) - Open Academic Graph (OAG) is a large knowledge graph unifying two billion-scale academic graphs: Microsoft Academic Graph (MAG) and AMiner.
* [DBPedia](https://wiki.dbpedia.org/services-resources/datasets/dbpedia-datasets) - DBpedia data set uses a large multi-domain ontology which has been derived from Wikipedia as well as localized versions of DBpedia in more than 100 languages.
* [Microsoft Academic Knowledge Graph](http://ma-graph.org/) - Microsoft Academic Knowledge Graph (MAKG), a large RDF data set with over eight billion triples with information about scientific publications and related entities, such as authors, institutions, journals, and fields of study. 
* [Crawler for GitHub](https://github.com/anvaka/allgithub) - Crawling github data for Software Galaxies visualisation

## [↑](#contents) Graph Papers

*Academic papers of large scale graph visualisation.*

* [Representation learning on graphs: Methods and applications](https://www-cs.stanford.edu/people/jure/pubs/graphrepresentation-ieee17.pdf) - Hamilton, W. L., Ying, R., & Leskovec, J. (2017). Representation learning on graphs: Methods and applications. IEEE Data Eng. Bull. 2017.

## [↑](#contents) Articles
*Articles on visualisation, UI/UX and software interfaces.*

* [Interfaces That Help Machine Learning](https://jmohsenin.com/interfaces-for-ml) - Jackson Mohsenin. (Oct 2020). An article about how ML and product design can work together to provide better signals for ML training (TikTok VS Twitter, gamification) and to provide a better interface to display ML inference in a good light (Netflix VS Hulu).