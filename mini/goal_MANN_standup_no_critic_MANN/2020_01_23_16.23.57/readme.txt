Physics-frequency: 1000
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
critic-weight-decay: 1e-06
dsr-gait-period: 0.6
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
env-id: HumanoidBalanceFilter-v0
bullet-default-PD: False
train-step-num: 1
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
test-num: 4
tau: 0.001
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
epoch-step-num: 5000000
task-weight: 0.2
critic-l2-reg: 0.0003
LLC-frequency: 500
gamma: 0.986
max-test-time: 10
max-step-num: 2500000000
state-dim: 25
actor-layer-size: [256, 256]
total-step-num: 2500000000
loss-output-smooth-coeff: 8.0
joint-interpolation: True
filter-torque: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-dim: 12
interpolation: False
record-start-size: 10000.0
imitation-weight: 0.4
gating-layer-size: [128, 128]
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
filter-action: True
epoch-num: 500
render-eval: False
loss-output-bound-coeff: 0.0
n-step: 1
loss-output-diff-coeff: 0
replay-ratio: 1
prioritized-exp-replay: True
reward-scale: 0.1
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
squash-action: True
critic-layer-size: [256, 256]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
max-train-time: 10
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
dsr-gait-freq: 1.667
actor-lr: 0.0003
expert-num: 8
replay-start-size: 10000
batch-size: 128
HLC-frequency: 25
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
goal-weight: 0.4
gating-activation-fn: ['relu', 'relu', 'None']
