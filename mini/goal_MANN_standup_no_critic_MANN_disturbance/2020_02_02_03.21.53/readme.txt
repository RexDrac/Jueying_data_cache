replay-buffer-size: 1000000
n-step: 1
imitation-weight: 0.4
tau: 0.001
replay-start-size: 10000
train-step-num: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
reward-scale: 0.1
squash-action: True
critic-weight-decay: 1e-06
replay-ratio: 1
dsr-gait-period: 0.6
gating-layer-size: [128, 128]
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
loss-entropy-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
joint-interpolation: True
actor-layer-size: [256, 256]
gamma: 0.986
epoch-step-num: 5000000
batch-size: 128
filter-torque: False
render-eval: False
total-step-num: 2500000000
critic-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-episode-num: 5000000
action-dim: 12
actor-weight-decay: 1e-06
epoch-num: 500
critic-lr: 0.0003
filter-action: True
dsr-gait-freq: 1.667
max-train-time: 10
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
goal-weight: 0.4
prioritized-exp-replay: True
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
critic-l2-reg: 0.0003
LLC-frequency: 500
state-dim: 25
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
task-weight: 0.2
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
max-path-num: 20
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
record-start-size: 10000.0
actor-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
Physics-frequency: 1000
loss-output-diff-coeff: 0
test-num: 4
loss-output-bound-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
