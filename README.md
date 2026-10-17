WebGL Forward+ and Clustered Deferred Shading
======================

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 4**

* Yanfu Ou
* Tested on: **Google Chrome Version 155.0.8059.39 ** on
  Ubuntu 24.04LTS, Ryzen 7 7840 @ 2.5GHz 64GB DDR4, RTX 5070 8GB

## Live Demo

[![media/live-web-demo.png](media/live-web-demo.png)](https://www.yanfuou.com/Project4-WebGPU-Forward-Plus-and-Clustered-Deferred-Yanfu/)

See the renderings live by clicking on the image above or [here](https://www.yanfuou.com/Project4-WebGPU-Forward-Plus-and-Clustered-Deferred-Yanfu/).  
## Demo GIF

#### Native
![Native](media/Proj4-native.gif)

#### Forward Plus
![Forward Plus](media/Proj4-Forward-Plus.gif)

#### Cluster Deferred
![Cluster Deferred](media/Proj4-Clustered-Deferred.gif)


## Performance Analysis
![chart](media/Number%20of%20Lights%20vs%20Render%20Times.png)

| Number of Lights   | Clustered Deferred(ms) | Forward(ms) | Native(ms) |
| :---- | :-------------------- | :------ | :-------- |
| 50    | 6                     | 6       | 7         |
| 100   | 6                     | 6       | 13        |
| 200   | 6                     | 6       | 24        |
| 300   | 6                     | 6       | 35        |
| 400   | 6                     | 6       | 53        |
| 500   | 6                     | 7       | 57        |
| 600   | 6                     | 8       | 73        |
| 700   | 6                     | 9       | 80        |
| 800   | 6                     | 10      | 91        |
| 900   | 6                     | 11      | 104       |
| 1000  | 6                     | 11      | 113       |
| 1300  | 6                     | 12      | 147       |
| 1600  | 7                     | 16      | 179       |
| 1900  | 8                     | 17      | 213       |
| 2100  | 9                     | 25      | 238       |
| 2500  | 9                     | 24      | 283       |
| 3000  | 12                    | 30      | 335       |
| 3500  | 12                    | 31      | 392       |
| 4000  | 12                    | 34      | 447       |
| 4500  | 14                    | 40      | 504       |
| 5000  | 14                    | 47      | 560       |



### Credits

- [Vite](https://vitejs.dev/)
- [loaders.gl](https://loaders.gl/)
- [dat.GUI](https://github.com/dataarts/dat.gui)
- [stats.js](https://github.com/mrdoob/stats.js)
- [wgpu-matrix](https://github.com/greggman/wgpu-matrix)
