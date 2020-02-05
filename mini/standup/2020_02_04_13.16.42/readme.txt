normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-train-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
joint-interpolation: True
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
replay-start-size: 10000
interpolation: False
squash-action: True
action-dim: 12
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
gating-activation-fn: ['relu', 'relu', 'None']
state-dim: 18
train-step-num: 1
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
render-eval: False
task-weight: 0.0
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
epoch-step-num: 5000000
filter-action: True
max-test-time: 10
expert-num: 4
test-num: 4
loss-output-smooth-coeff: 2.0
actor-weight-decay: 1e-06
epoch-num: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
reward-scale: 0.1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
filter-torque: False
record-start-size: 10000.0
gating-layer-size: [32, 32]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-diff-coeff: 0
max-path-step: 5000
critic-l2-reg: 0.0003
bullet-default-PD: False
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
critic-lr: 0.0003
HLC-frequency: 25
n-step: 1
imitation-weight: 1.0
tau: 0.001
gamma: 0.995
replay-buffer-size: 1000000
actor-l2-reg: 0.0003
max-episode-num: 5000000
max-step-num: 2500000000
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
max-path-num: 20
gating-index: None
LLC-frequency: 500
expert-index: None
critic-layer-size: [256, 256]
