env-id: HumanoidBalanceFilter-v0
train-step-num: 1
critic-weight-decay: 1e-06
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
tau: 0.001
n-step: 1
render-eval: False
max-step-num: 2500000000
replay-start-size: 10000
expert-num: 8
actor-layer-size: [256, 256]
max-path-num: 20
state-dim: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
gamma: 0.986
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
action-dim: 12
max-test-time: 10
joint-interpolation: True
reward-scale: 0.1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-entropy-coeff: 0.0
replay-ratio: 1
goal-weight: 0.4
max-episode-num: 5000000
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
dsr-gait-period: 0.6
critic-lr: 0.0003
batch-size: 128
loss-output-diff-coeff: 0
Physics-frequency: 1000
test-num: 4
squash-action: True
actor-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
actor-lr: 0.0003
epoch-step-num: 5000000
filter-torque: False
imitation-weight: 0.4
max-train-time: 10
bullet-default-PD: False
interpolation: False
record-start-size: 10000.0
task-weight: 0.2
actor-weight-decay: 1e-06
max-path-step: 5000
epoch-num: 500
dsr-gait-freq: 1.667
rollout-step-num: 1
LLC-frequency: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
prioritized-exp-replay: True
total-step-num: 2500000000
loss-output-smooth-coeff: 8.0
critic-l2-reg: 0.0003
gating-layer-size: [128, 128]
critic-layer-size: [256, 256]
