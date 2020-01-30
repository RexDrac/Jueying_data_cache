actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
loss-output-bound-coeff: 0.0
actor-l2-reg: 0.0003
max-episode-num: 5000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
Physics-frequency: 1000
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-diff-coeff: 0
max-path-step: 5000
action-dim: 12
epoch-num: 500
reward-scale: 0.1
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
total-step-num: 2500000000
gating-layer-size: [128, 128]
critic-lr: 0.0003
max-train-time: 10
record-start-size: 10000.0
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
test-num: 4
LLC-frequency: 500
gamma: 0.986
actor-lr: 0.0003
goal-weight: 0.4
replay-start-size: 10000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
max-step-num: 2500000000
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
batch-size: 128
imitation-weight: 0.4
dsr-gait-freq: 1.667
filter-action: True
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
expert-num: 8
loss-output-smooth-coeff: 2.0
state-dim: 25
n-step: 1
task-weight: 0.2
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
rollout-step-num: 1
filter-torque: False
actor-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
joint-interpolation: True
actor-layer-size: [256, 256]
max-test-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
render-eval: False
replay-ratio: 1
HLC-frequency: 25
critic-weight-decay: 1e-06
epoch-step-num: 5000000
max-path-num: 20
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
squash-action: True
prioritized-exp-replay: True
