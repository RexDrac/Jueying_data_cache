actor-layer-size: [256, 256]
Physics-frequency: 1000
goal-weight: 0.4
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 8
actor-lr: 0.0003
HLC-frequency: 25
gamma: 0.986
replay-buffer-size: 1000000
critic-lr: 0.0003
n-step: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
epoch-num: 500
squash-action: True
prioritized-exp-replay: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
gating-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
task-weight: 0.2
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
max-step-num: 2500000000
action-dim: 12
interpolation: False
epoch-step-num: 5000000
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-train-time: 10
replay-ratio: 1
imitation-weight: 0.4
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
filter-torque: False
tau: 0.001
critic-layer-size: [256, 256]
replay-start-size: 10000
max-path-step: 5000
reward-scale: 0.1
train-step-num: 1
dsr-gait-period: 0.6
render-eval: False
max-test-time: 10
env-id: HumanoidBalanceFilter-v0
joint-interpolation: True
loss-output-diff-coeff: 0
critic-weight-decay: 1e-06
test-num: 4
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
critic-l2-reg: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
record-start-size: 10000.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
actor-weight-decay: 1e-06
dsr-gait-freq: 1.667
gating-layer-size: [128, 128]
loss-output-smooth-coeff: 2.0
bullet-default-PD: False
rollout-step-num: 1
loss-output-bound-coeff: 0.0
actor-l2-reg: 0.0003
