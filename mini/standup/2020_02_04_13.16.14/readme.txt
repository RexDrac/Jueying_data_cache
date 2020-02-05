critic-l2-reg: 0.0003
gating-index: None
epoch-num: 500
env-id: HumanoidBalanceFilter-v0
n-step: 1
max-path-step: 5000
gating-layer-size: [32, 32]
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
interpolation: False
critic-lr: 0.0003
actor-lr: 0.0003
replay-start-size: 10000
bullet-default-PD: False
loss-output-bound-coeff: 0.0
squash-action: True
total-step-num: 2500000000
train-step-num: 1
test-num: 4
replay-ratio: 1
max-step-num: 2500000000
record-start-size: 10000.0
actor-l2-reg: 0.0003
loss-entropy-coeff: 0.0
task-weight: 0.0
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
actor-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
reward-scale: 0.1
expert-index: None
max-path-num: 20
rollout-step-num: 1
max-episode-num: 5000000
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
tau: 0.001
render-eval: False
Physics-frequency: 1000
replay-buffer-size: 1000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
action-dim: 12
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
critic-weight-decay: 1e-06
critic-layer-size: [256, 256]
joint-interpolation: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
imitation-weight: 1.0
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
epoch-step-num: 5000000
state-dim: 18
max-test-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
HLC-frequency: 25
gamma: 0.995
filter-torque: False
batch-size: 128
