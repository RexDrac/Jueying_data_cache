bullet-default-PD: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-l2-reg: 0.0003
interpolation: False
n-step: 1
record-start-size: 10000.0
train-step-num: 1
epoch-num: 500
rollout-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 25
prioritized-exp-replay: True
gating-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
max-episode-num: 5000000
action-dim: 12
test-num: 4
critic-l2-reg: 0.0003
filter-torque: False
total-step-num: 2500000000
imitation-weight: 0.4
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
render-eval: False
epoch-step-num: 5000000
squash-action: True
critic-layer-size: [256, 256]
max-path-num: 20
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-start-size: 10000
dsr-gait-freq: 1.667
loss-output-smooth-coeff: 8.0
tau: 0.001
dsr-gait-period: 0.6
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
max-path-step: 5000
critic-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 100
actor-lr: 0.0003
max-train-time: 10
max-test-time: 10
Physics-frequency: 1000
max-step-num: 2500000000
loss-output-bound-coeff: 0.0
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
reward-scale: 0.1
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
gating-layer-size: [128, 128]
critic-weight-decay: 1e-06
goal-weight: 0.4
critic-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
actor-layer-size: [256, 256]
loss-output-diff-coeff: 0
filter-action: True
gamma: 0.997
replay-ratio: 1
task-weight: 0.2
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
batch-size: 128
