max-test-time: 10
max-episode-num: 5000000
max-step-num: 2500000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
rollout-step-num: 1
loss-output-smooth-coeff: 2.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
Physics-frequency: 1000
replay-buffer-size: 1000000
critic-weight-decay: 1e-06
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
epoch-num: 500
n-step: 1
test-num: 4
batch-size: 128
record-start-size: 10000.0
prioritized-exp-replay: True
imitation-weight: 0.4
gating-layer-size: [128, 128]
max-path-step: 5000
task-weight: 0.2
squash-action: True
max-path-num: 20
goal-weight: 0.4
loss-output-bound-coeff: 0.0
state-dim: 25
filter-action: True
render-eval: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
train-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-period: 0.6
env-id: HumanoidBalanceFilter-v0
actor-layer-size: [256, 256]
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
joint-interpolation: True
actor-l2-reg: 0.0003
actor-lr: 0.0003
filter-torque: False
bullet-default-PD: False
critic-l2-reg: 0.0003
replay-start-size: 10000
loss-output-diff-coeff: 0
gamma: 0.986
epoch-step-num: 5000000
critic-lr: 0.0003
action-dim: 12
critic-layer-size: [256, 256]
interpolation: False
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
expert-num: 8
dsr-gait-freq: 1.667
replay-ratio: 1
HLC-frequency: 25
tau: 0.001
