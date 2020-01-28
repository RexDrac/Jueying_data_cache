squash-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
prioritized-exp-replay: True
joint-interpolation: True
interpolation: False
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
goal-weight: 0.4
imitation-weight: 0.4
tau: 0.001
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 8
actor-layer-size: [256, 256]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
rollout-step-num: 1
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
reward-scale: 0.1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
record-start-size: 10000.0
actor-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
actor-weight-decay: 1e-06
critic-lr: 0.0003
total-step-num: 2500000000
critic-l2-reg: 0.0003
gating-layer-size: [128, 128]
gamma: 0.986
render-eval: False
epoch-step-num: 5000000
loss-output-diff-coeff: 0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
dsr-gait-period: 0.6
loss-output-smooth-coeff: 2.0
max-step-num: 2500000000
filter-torque: False
task-weight: 0.2
max-path-step: 5000
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
filter-action: True
dsr-gait-freq: 1.667
actor-lr: 0.0003
bullet-default-PD: False
loss-output-bound-coeff: 0.0
HLC-frequency: 25
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
batch-size: 128
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 25
test-num: 4
loss-entropy-coeff: 0.0
replay-buffer-size: 1000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
max-path-num: 20
max-train-time: 10
replay-start-size: 10000
n-step: 1
replay-ratio: 1
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
