max-test-time: 10
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
max-step-num: 2500000000
bullet-default-PD: False
critic-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
actor-lr: 0.0003
replay-start-size: 10000
critic-layer-size: [256, 256]
Physics-frequency: 1000
filter-action: True
actor-l2-reg: 0.0003
max-path-num: 20
batch-size: 128
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
imitation-weight: 0.4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
task-weight: 0.2
critic-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
prioritized-exp-replay: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [128, 128]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-entropy-coeff: 0.0
goal-weight: 0.4
test-num: 4
max-train-time: 10
loss-output-bound-coeff: 0.0
render-eval: False
rollout-step-num: 1
loss-output-diff-coeff: 0
HLC-frequency: 25
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-lr: 0.0003
dsr-gait-freq: 1.667
interpolation: False
record-start-size: 10000.0
gamma: 0.986
actor-layer-size: [256, 256]
max-path-step: 5000
actor-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
epoch-step-num: 5000000
action-dim: 12
n-step: 1
reward-scale: 0.1
squash-action: True
epoch-num: 500
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
actor-weight-decay: 1e-06
dsr-gait-period: 0.6
train-step-num: 1
joint-interpolation: True
state-dim: 25
replay-ratio: 1
critic-l2-reg: 0.0003
