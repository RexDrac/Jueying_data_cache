loss-output-bound-coeff: 0.0
max-test-time: 10
gamma: 0.955
n-step: 1
train-step-num: 1
loss-output-diff-coeff: 0
critic-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
total-step-num: 2500000000
epoch-step-num: 5000000
rollout-step-num: 1
gating-layer-size: [32, 32]
action-dim: 12
filter-action: True
imitation-weight: 0.5
max-path-step: 5000
tau: 0.001
actor-layer-size: [256, 256]
filter-torque: False
dsr-gait-freq: 1.667
record-start-size: 10000.0
replay-ratio: 1
replay-buffer-size: 1000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 25
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
max-episode-num: 5000000
render-eval: False
max-train-time: 10
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
max-path-num: 20
epoch-num: 500
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
task-weight: 0.5
loss-output-smooth-coeff: 2.0
joint-interpolation: True
actor-weight-decay: 1e-06
state-dim: 23
env-id: HumanoidBalanceFilter-v0
actor-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
gating-index: None
replay-start-size: 10000
test-num: 4
squash-action: True
LLC-frequency: 500
prioritized-exp-replay: True
actor-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
bullet-default-PD: False
interpolation: False
loss-entropy-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
critic-layer-size: [256, 256]
critic-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: None
batch-size: 128
Physics-frequency: 1000
