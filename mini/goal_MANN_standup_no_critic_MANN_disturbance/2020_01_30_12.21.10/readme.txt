state-dim: 25
critic-layer-size: [256, 256]
expert-num: 8
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
critic-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.986
max-path-num: 20
test-num: 4
gating-layer-size: [128, 128]
loss-entropy-coeff: 0.0
filter-action: True
actor-layer-size: [256, 256]
max-path-step: 5000
squash-action: True
goal-weight: 0.4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
prioritized-exp-replay: True
render-eval: False
actor-l2-reg: 0.0003
record-start-size: 10000.0
tau: 0.001
replay-ratio: 1
actor-lr: 0.0003
actor-weight-decay: 1e-06
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
critic-lr: 0.0003
n-step: 1
Physics-frequency: 1000
task-weight: 0.2
rollout-step-num: 1
joint-interpolation: True
dsr-gait-period: 0.6
dsr-gait-freq: 1.667
epoch-step-num: 5000000
loss-output-smooth-coeff: 2.0
train-step-num: 1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
env-id: HumanoidBalanceFilter-v0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-episode-num: 5000000
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
max-train-time: 10
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
HLC-frequency: 25
critic-weight-decay: 1e-06
critic-l2-reg: 0.0003
max-test-time: 10
replay-buffer-size: 1000000
epoch-num: 500
replay-start-size: 10000
imitation-weight: 0.4
LLC-frequency: 500
filter-torque: False
loss-output-diff-coeff: 0
interpolation: False
reward-scale: 0.1
