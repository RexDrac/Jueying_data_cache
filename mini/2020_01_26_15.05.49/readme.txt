actor-l2-reg: 0.0003
total-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
max-step-num: 2500000000
epoch-step-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-weight-decay: 1e-06
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
test-num: 4
task-weight: 0.2
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-layer-size: [256, 256]
reward-scale: 0.1
actor-lr: 0.0003
batch-size: 128
record-start-size: 10000.0
filter-torque: False
filter-action: True
HLC-frequency: 25
loss-output-bound-coeff: 0.0
max-test-time: 10
state-dim: 25
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
imitation-weight: 0.4
LLC-frequency: 500
max-path-step: 5000
replay-buffer-size: 1000000
render-eval: False
action-dim: 12
dsr-gait-period: 0.6
train-step-num: 1
Physics-frequency: 1000
critic-weight-decay: 1e-06
epoch-num: 500
critic-l2-reg: 0.0003
interpolation: False
loss-output-diff-coeff: 0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-lr: 0.0003
replay-start-size: 10000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [128, 128]
max-episode-num: 5000000
prioritized-exp-replay: True
max-train-time: 10
critic-layer-size: [256, 256]
n-step: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
loss-output-smooth-coeff: 8.0
squash-action: True
replay-ratio: 1
joint-interpolation: True
goal-weight: 0.4
rollout-step-num: 1
tau: 0.001
loss-entropy-coeff: 0.0
dsr-gait-freq: 1.667
gamma: 0.986
