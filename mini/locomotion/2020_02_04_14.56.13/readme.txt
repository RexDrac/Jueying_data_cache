actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
actor-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
interpolation: False
test-num: 4
dsr-gait-period: 0.6
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
joint-interpolation: True
replay-ratio: 1
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
critic-l2-reg: 0.0003
max-path-step: 5000
record-start-size: 10000.0
filter-action: True
expert-num: 4
prioritized-exp-replay: True
render-eval: False
max-episode-num: 5000000
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
HLC-frequency: 25
max-path-num: 20
total-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-diff-coeff: 0
reward-scale: 0.1
LLC-frequency: 500
action-dim: 12
epoch-step-num: 5000000
critic-lr: 0.0003
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
env-id: HumanoidBalanceFilter-v0
batch-size: 128
expert-index: None
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
epoch-num: 500
replay-start-size: 10000
critic-activation-fn: ['relu', 'relu', 'None']
n-step: 1
task-weight: 0.5
actor-l2-reg: 0.0003
tau: 0.001
train-step-num: 1
max-test-time: 10
loss-entropy-coeff: 0.0
gating-layer-size: [32, 32]
critic-weight-decay: 1e-06
gating-index: None
replay-buffer-size: 1000000
gamma: 0.955
Physics-frequency: 1000
actor-lr: 0.0003
state-dim: 23
critic-layer-size: [256, 256]
imitation-weight: 0.5
squash-action: True
dsr-gait-freq: 1.667
rollout-step-num: 1
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
bullet-default-PD: False
