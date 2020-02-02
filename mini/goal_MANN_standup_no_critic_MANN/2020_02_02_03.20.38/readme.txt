actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
critic-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
joint-interpolation: True
max-path-num: 20
actor-weight-decay: 1e-06
HLC-frequency: 25
batch-size: 128
dsr-gait-period: 0.6
critic-l2-reg: 0.0003
bullet-default-PD: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
prioritized-exp-replay: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
tau: 0.001
total-step-num: 2500000000
epoch-step-num: 5000000
epoch-num: 500
actor-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
replay-buffer-size: 1000000
actor-lr: 0.0003
actor-l2-reg: 0.0003
critic-layer-size: [256, 256]
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
dsr-gait-freq: 1.667
LLC-frequency: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-layer-size: [256, 256]
task-weight: 0.2
Physics-frequency: 1000
squash-action: True
goal-weight: 0.4
loss-output-bound-coeff: 0.0
n-step: 1
critic-weight-decay: 1e-06
reward-scale: 0.1
filter-action: True
interpolation: False
max-episode-num: 5000000
max-step-num: 2500000000
expert-num: 8
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
rollout-step-num: 1
max-train-time: 10
loss-entropy-coeff: 0.0
loss-output-smooth-coeff: 2.0
max-test-time: 10
action-dim: 12
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
max-path-step: 5000
train-step-num: 1
gating-layer-size: [128, 128]
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
render-eval: False
state-dim: 25
env-id: HumanoidBalanceFilter-v0
imitation-weight: 0.4
record-start-size: 10000.0
