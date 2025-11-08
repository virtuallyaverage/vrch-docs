# Internal Node Map

The Node Map is an internal representation of haptic signals. It doesn't need to be understood for simple haptic algorithms and projects, but it is advised to become familiar with it before attempting any advanced input or device designing.

Since haptic solutions are going to be applied to a human body and most human bodies are relatively similar as far as unique shapes in the universe go, it is possible to map one humanoid input to another output. If it is known on what part of the body a motor is, we end up with a dimensionless abstraction of the point. A point described like; on the torso,half the way up the spine, facing forwards, becomes a representation of a point on the body regardless of it's shape.

## The Standard

While it's great to have a completely abstract representation of a human body, we need a solid translation layer to be able to go between this abstraction to real feedback values. To do this we plot our abstract points onto a "standard" model 
