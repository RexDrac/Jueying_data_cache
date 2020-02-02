filter-torque: False
HLC-frequency: 25
epoch-num: 500
state-dim: 25
max-test-time: 10
loss-output-diff-coeff: 0
task-weight: 0.2
actor-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
imitation-weight: 0.4
gating-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
goal-weight: 0.4
max-train-time: 10
loss-output-smooth-coeff: 2.0
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
action-dim: 12
total-step-num: 2500000000
gamma: 0.986
record-start-size: 10000.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
tau: 0.001
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-step-num: 2500000000
max-path-step: 5000
actor-weight-decay: 1e-06
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
replay-ratio: 1
rollout-step-num: 1
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
dsr-gait-freq: 1.667
train-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
test-num: 4
LLC-frequency: 500
epoch-step-num: 5000000
max-path-num: 20
critic-l2-reg: 0.0003
gating-layer-size: [128, 128]
expert-num: 8
interpolation: False
replay-buffer-size: 1000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
n-step: 1
Physics-frequency: 1000
max-episode-num: 5000000
critic-layer-size: [256, 256]
dsr-gait-period: 0.6
render-eval: False
prioritized-exp-replay: True
reward-scale: 0.1
loss-entropy-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
squash-action: True
