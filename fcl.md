# 碰撞检测
    # include  < fcl/BVH/BVH_model.h >  描述网格模型或点云模型（被视为网格的降级版本）的边界层次的类 
    broadphase Broadphase 的目的，是使用廉价的计算来产生可能的碰撞，并剔除不能发生的接触，从而减少你的工作
    # include  < fcl/broadphase/broadphase_dynamic_AABB_tree.h > 
    动态 AABB 树是一种 无边界 的 broadphase ，这意味着它不像其他一些 broadphases 那样施加严格的边界限制，例如显式网格和隐式网格。
    https://allenchou.net/2014/02/game-physics-broadphase-dynamic-aabb-tree/
    # include  < fcl/broadphase/broadphase_bruteforce.h > 
    # include  < fcl/collision.h > 
    # include  < fcl/distance.h > 
    # include  < fcl/shape/geometric_shapes.h > 
    # include  < kdl_parser/kdl_parser.hpp > 
    # include  < kdl/chainfksolverpos_recursive.hpp > 
    # include  < urdf/model.h >  模型