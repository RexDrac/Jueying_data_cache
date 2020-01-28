actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
total-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-diff-coeff: 0
squash-action: True
actor-lr: 0.0003
filter-action: True
filter-torque: False
actor-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
max-train-time: 10
bullet-default-PD: False
task-weight: 0.2
tau: 0.001
Physics-frequency: 1000
n-step: 1
prioritized-exp-replay: True
train-step-num: 1
loss-output-bound-coeff: 0.0
epoch-num: 500
dsr-gait-period: 0.6
max-episode-num: 5000000
actor-l2-reg: 0.0003
actor-layer-size: [256, 256]
reward-scale: 0.1
env-id: HumanoidBalanceFilter-v0
max-path-step: 5000
replay-start-size: 10000
test-num: 4
actor-weight-decay: 1e-06
rollout-step-num: 1
imitation-weight: 0.4
max-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-test-time: 10
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
state-dim: 25
replay-buffer-size: 1000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 8
critic-l2-reg: 0.0003
render-eval: False
gamma: 0.986
HLC-frequency: 25
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 8.0
joint-interpolation: True
batch-size: 128
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
interpolation: False
record-start-size: 10000.0
dsr-gait-freq: 1.667
goal-weight: 0.4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [128, 128]
LLC-frequency: 500
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
critic-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-entropy-coeff: 0.0
critic-lr: 0.0003
epoch-step-num: 5000000
critic-weight-decay: 1e-06
