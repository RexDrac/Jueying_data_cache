Physics-frequency: 1000
goal-weight: 0.4
expert-num: 8
squash-action: True
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
HLC-frequency: 25
interpolation: False
env-id: HumanoidBalanceFilter-v0
imitation-weight: 0.4
max-episode-num: 5000000
critic-weight-decay: 1e-06
total-step-num: 2500000000
epoch-step-num: 5000000
max-path-num: 20
dsr-gait-freq: 1.667
max-step-num: 2500000000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
test-num: 4
loss-output-diff-coeff: 0
actor-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
bullet-default-PD: False
task-weight: 0.2
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
gamma: 0.986
replay-start-size: 10000
critic-lr: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-l2-reg: 0.0003
actor-layer-size: [256, 256]
train-step-num: 1
epoch-num: 500
n-step: 1
gating-layer-size: [128, 128]
batch-size: 128
actor-weight-decay: 1e-06
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
dsr-gait-period: 0.6
tau: 0.001
max-train-time: 10
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
record-start-size: 10000.0
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
action-dim: 12
critic-l2-reg: 0.0003
rollout-step-num: 1
filter-action: True
state-dim: 25
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
max-test-time: 10
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
