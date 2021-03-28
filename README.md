# flower clustering
Training a simple ConvNet to classify fruits and vegetables with PyTorch

[Dataset](https://www.kaggle.com/olgabelitskaya/flower-color-images) is available in kaggle. Download the dataset, unzip it to where .ipynb file is.

In this dataset, there are 20 classes and 603 flower images.

Clustering achieved by 3 steps.

- Extract features from vgg-16 (remove the last relu-dropout-linear layer) for every single image.
- Apply PCA to decrease the number of features from 4096 to 400.
- Apply kmeans algorithm with k = 20


Install the required libraries
```bash
$ pip install -r requirements.txt
```

Then run the script cell by cell.


# Results
Clusters (each column is a cluster)

Some clusters doesn't have 10 images, that's why this subplot is not filled.
| ![plot-all.png](plot-all.png) | 
|:--:| 
| clustering results |


## Clusters

### Cluster 0
| ![/cluster-imgs/0.png](/cluster-imgs/0.png) | 
|:--:| 
| Cluster 0 |

### Cluster 1
| ![/cluster-imgs/1.png](/cluster-imgs/1.png) | 
|:--:| 
| Cluster 1 |

### Cluster 2
| ![/cluster-imgs/2.png](/cluster-imgs/2.png) | 
|:--:| 
| Cluster 2 |

### Cluster 3
| ![/cluster-imgs/3.png](/cluster-imgs/3.png) | 
|:--:| 
| Cluster 3 |

### Cluster 4
| ![/cluster-imgs/4.png](/cluster-imgs/4.png) | 
|:--:| 
| Cluster 4 |

### Cluster 5
| ![/cluster-imgs/5.png](/cluster-imgs/5.png) | 
|:--:| 
| Cluster 5 |

### Cluster 6
| ![/cluster-imgs/6.png](/cluster-imgs/6.png) | 
|:--:| 
| Cluster 6 |

### Cluster 7
| ![/cluster-imgs/7.png](/cluster-imgs/7.png) | 
|:--:| 
| Cluster 7 |

### Cluster 8
| ![/cluster-imgs/8.png](/cluster-imgs/8.png) | 
|:--:| 
| Cluster 8 |

### Cluster 9
| ![/cluster-imgs/9.png](/cluster-imgs/9.png) | 
|:--:| 
| Cluster 9 |

### Cluster 10
| ![/cluster-imgs/10.png](/cluster-imgs/10.png) | 
|:--:| 
| Cluster 10 |

### Cluster 11
| ![/cluster-imgs/11.png](/cluster-imgs/11.png) | 
|:--:| 
| Cluster 11 |

### Cluster 12
| ![/cluster-imgs/12.png](/cluster-imgs/12.png) | 
|:--:| 
| Cluster 12 |

### Cluster 13
| ![/cluster-imgs/13.png](/cluster-imgs/13.png) | 
|:--:| 
| Cluster 13 |

### Cluster 14
| ![/cluster-imgs/14.png](/cluster-imgs/14.png) | 
|:--:| 
| Cluster 14 |

### Cluster 15
| ![/cluster-imgs/15.png](/cluster-imgs/15.png) | 
|:--:| 
| Cluster 15 |

### Cluster 16
| ![/cluster-imgs/16.png](/cluster-imgs/16.png) | 
|:--:| 
| Cluster 16 |

### Cluster 17
| ![/cluster-imgs/17.png](/cluster-imgs/17.png) | 
|:--:| 
| Cluster 17 |

### Cluster 18
| ![/cluster-imgs/18.png](/cluster-imgs/18.png) | 
|:--:| 
| Cluster 18 |

### Cluster 19
| ![/cluster-imgs/19.png](/cluster-imgs/19.png) | 
|:--:| 
| Cluster 19 |
