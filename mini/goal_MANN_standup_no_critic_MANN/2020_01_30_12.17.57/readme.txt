render-eval: False
loss-output-bound-coeff: 0.0
gating-layer-size: [128, 128]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
loss-entropy-coeff: 0.0
critic-l2-reg: 0.0003
state-dim: 25
train-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
n-step: 1
max-episode-num: 5000000
expert-num: 8
tau: 0.001
max-step-num: 2500000000
max-train-time: 10
bullet-default-PD: False
task-weight: 0.2
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
record-start-size: 10000.0
epoch-num: 500
loss-output-smooth-coeff: 2.0
test-num: 4
critic-lr: 0.0003
replay-buffer-size: 1000000
gating-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
epoch-step-num: 5000000
gamma: 0.986
max-path-step: 5000
rollout-step-num: 1
LLC-frequency: 500
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
HLC-frequency: 25
actor-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
action-dim: 12
joint-interpolation: True
max-path-num: 20
loss-output-diff-coeff: 0
goal-weight: 0.4
filter-action: True
Physics-frequency: 1000
critic-weight-decay: 1e-06
imitation-weight: 0.4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-period: 0.6
interpolation: False
filter-torque: False
actor-lr: 0.0003
prioritized-exp-replay: True
max-test-time: 10
dsr-gait-freq: 1.667
actor-layer-size: [256, 256]
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
replay-ratio: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
total-step-num: 2500000000
squash-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
actor-l2-reg: 0.0003
