actor-activation-fn: ['relu', 'relu', 'None']
gating-index: None
tau: 0.001
epoch-num: 500
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
HLC-frequency: 25
gamma: 0.955
max-path-num: 20
expert-num: 4
filter-torque: False
loss-entropy-coeff: 0.0
max-test-time: 10
critic-weight-decay: 1e-06
action-dim: 12
max-step-num: 2500000000
actor-lr: 0.0003
max-path-step: 5000
critic-l2-reg: 0.0003
replay-start-size: 10000
rollout-step-num: 1
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
epoch-step-num: 5000000
max-train-time: 10
replay-ratio: 1
imitation-weight: 0.5
LLC-frequency: 500
actor-l2-reg: 0.0003
Physics-frequency: 1000
task-weight: 0.5
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
loss-output-smooth-coeff: 2.0
critic-activation-fn: ['relu', 'relu', 'None']
test-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
total-step-num: 2500000000
max-episode-num: 5000000
dsr-gait-freq: 1.667
train-step-num: 1
loss-output-diff-coeff: 0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
render-eval: False
prioritized-exp-replay: True
bullet-default-PD: False
interpolation: False
dsr-gait-period: 0.6
gating-layer-size: [32, 32]
state-dim: 23
squash-action: True
actor-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
env-id: HumanoidBalanceFilter-v0
expert-index: None
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
filter-action: True
