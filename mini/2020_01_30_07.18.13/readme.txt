actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-action: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
critic-layer-size: [256, 256]
Physics-frequency: 1000
gating-layer-size: [128, 128]
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
replay-start-size: 10000
max-path-step: 5000
action-dim: 12
loss-output-bound-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
critic-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
loss-output-diff-coeff: 0
batch-size: 128
loss-output-smooth-coeff: 2.0
expert-num: 8
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
gamma: 0.986
replay-ratio: 1
LLC-frequency: 500
actor-layer-size: [256, 256]
critic-lr: 0.0003
actor-lr: 0.0003
critic-weight-decay: 1e-06
critic-l2-reg: 0.0003
epoch-step-num: 5000000
record-start-size: 10000.0
squash-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
goal-weight: 0.4
imitation-weight: 0.4
max-test-time: 10
dsr-gait-freq: 1.667
task-weight: 0.2
render-eval: False
prioritized-exp-replay: True
reward-scale: 0.1
test-num: 4
replay-buffer-size: 1000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-weight-decay: 1e-06
dsr-gait-period: 0.6
actor-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
epoch-num: 500
rollout-step-num: 1
max-path-num: 20
max-train-time: 10
actor-l2-reg: 0.0003
max-episode-num: 5000000
interpolation: False
HLC-frequency: 25
tau: 0.001
