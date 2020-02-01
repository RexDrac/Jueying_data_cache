actor-layer-size: [256, 256]
replay-start-size: 10000
critic-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
max-train-time: 10
bullet-default-PD: False
max-episode-num: 5000000
max-path-step: 5000
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-layer-size: [128, 128]
max-test-time: 10
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-path-num: 20
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
LLC-frequency: 500
batch-size: 128
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
rollout-step-num: 1
env-id: HumanoidBalanceFilter-v0
filter-action: True
goal-weight: 0.4
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
HLC-frequency: 25
actor-weight-decay: 1e-06
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
actor-lr: 0.0003
tau: 0.001
total-step-num: 2500000000
max-step-num: 2500000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
joint-interpolation: True
gamma: 0.986
dsr-gait-freq: 1.667
expert-num: 8
loss-output-bound-coeff: 0.0
epoch-num: 500
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
action-dim: 12
reward-scale: 0.1
render-eval: False
imitation-weight: 0.4
loss-output-smooth-coeff: 2.0
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
loss-entropy-coeff: 0.0
task-weight: 0.2
n-step: 1
Physics-frequency: 1000
critic-lr: 0.0003
train-step-num: 1
prioritized-exp-replay: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-diff-coeff: 0
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
epoch-step-num: 5000000
interpolation: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
state-dim: 25
actor-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
