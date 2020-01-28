state-dim: 25
replay-ratio: 1
max-path-num: 20
dsr-gait-freq: 1.667
train-step-num: 1
n-step: 1
loss-output-diff-coeff: 0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-period: 0.6
test-num: 4
joint-interpolation: True
max-train-time: 10
reward-scale: 0.1
filter-torque: False
critic-lr: 0.0003
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
imitation-weight: 0.4
max-episode-num: 5000000
gating-layer-size: [128, 128]
filter-action: True
replay-buffer-size: 1000000
critic-l2-reg: 0.0003
task-weight: 0.2
rollout-step-num: 1
interpolation: False
actor-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
HLC-frequency: 25
max-test-time: 10
expert-num: 8
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
record-start-size: 10000.0
epoch-num: 500
total-step-num: 2500000000
squash-action: True
critic-layer-size: [256, 256]
loss-output-bound-coeff: 0.0
Physics-frequency: 1000
max-path-step: 5000
prioritized-exp-replay: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.986
actor-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
bullet-default-PD: False
max-step-num: 2500000000
goal-weight: 0.4
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 8.0
replay-start-size: 10000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
env-id: HumanoidBalanceFilter-v0
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
actor-weight-decay: 1e-06
batch-size: 128
critic-weight-decay: 1e-06
epoch-step-num: 5000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
