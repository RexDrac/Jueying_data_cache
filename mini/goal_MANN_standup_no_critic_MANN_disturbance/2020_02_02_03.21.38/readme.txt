max-path-num: 20
joint-interpolation: True
filter-action: True
dsr-gait-period: 0.6
critic-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
loss-output-diff-coeff: 0
squash-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
dsr-gait-freq: 1.667
render-eval: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
bullet-default-PD: False
imitation-weight: 0.4
gating-layer-size: [128, 128]
critic-layer-size: [256, 256]
train-step-num: 1
actor-weight-decay: 1e-06
total-step-num: 2500000000
epoch-step-num: 5000000
reward-scale: 0.1
LLC-frequency: 500
tau: 0.001
max-test-time: 10
action-dim: 12
loss-output-smooth-coeff: 2.0
prioritized-exp-replay: True
critic-lr: 0.0003
actor-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
interpolation: False
replay-buffer-size: 1000000
rollout-step-num: 1
replay-start-size: 10000
filter-torque: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
expert-num: 8
Physics-frequency: 1000
epoch-num: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
HLC-frequency: 25
actor-lr: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
goal-weight: 0.4
record-start-size: 10000.0
max-path-step: 5000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
task-weight: 0.2
max-episode-num: 5000000
n-step: 1
max-train-time: 10
gamma: 0.986
max-step-num: 2500000000
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
critic-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
test-num: 4
state-dim: 25
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
