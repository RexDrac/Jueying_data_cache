actor-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
epoch-num: 500
replay-start-size: 10000
train-step-num: 1
critic-l2-reg: 0.0003
critic-weight-decay: 1e-06
test-num: 4
dsr-gait-freq: 1.667
max-path-num: 20
HLC-frequency: 25
max-episode-num: 5000000
dsr-gait-period: 0.6
imitation-weight: 0.4
max-step-num: 2500000000
actor-lr: 0.0003
rollout-step-num: 1
replay-buffer-size: 1000000
n-step: 1
replay-ratio: 1
actor-l2-reg: 0.0003
max-test-time: 10
goal-weight: 0.4
filter-torque: False
Physics-frequency: 1000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 25
env-id: HumanoidBalanceFilter-v0
actor-weight-decay: 1e-06
epoch-step-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.2
action-dim: 12
reward-scale: 0.1
loss-output-smooth-coeff: 2.0
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
joint-interpolation: True
max-train-time: 10
loss-output-bound-coeff: 0.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 8
squash-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
gamma: 0.986
interpolation: False
prioritized-exp-replay: True
record-start-size: 10000.0
max-path-step: 5000
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
batch-size: 128
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
bullet-default-PD: False
loss-output-diff-coeff: 0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-layer-size: [128, 128]
