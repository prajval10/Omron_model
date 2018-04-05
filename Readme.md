# Gazebo Model for Omron OS32C sensor

The STEP model of the sensor was downloaded from [here](http://www.omron.com.au/products/family/2717/download/cad.html). This was converted to .STL and then to .DAE in Blender.

## Model properties

1. Mass: 1.3 kg

2. Inertia Tensor is :

    | 0.001567 0.000000 0.000000 |

    | 0.000000 0.001532 -0.000059 |

    | 0.000000 -0.000059 0.001594 |

3. Sensor properties:

* Ray samples: 70
* Min angle : 45 degree
* Max angle : 225 degree
* Min Distance: 1.75m
* Max Distance: 10m
* Gaussian Noise: mean = 0; Standard deviation = 0.02

## Screenshot Images

## Installation

Clone the model into the gazebo models directory

`cd .gazebo/models`

`git clone git@gitlab.com:MS-Thesis/omron-model.git` 
