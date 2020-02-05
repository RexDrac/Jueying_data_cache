expert-num: 4
joint-interpolation: True
total-step-num: 2500000000
gamma: 0.995
critic-weight-decay: 1e-06
max-test-time: 10
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
imitation-weight: 1.0
gating-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
record-start-size: 10000.0
action-dim: 12
actor-lr: 0.0003
interpolation: False
LLC-frequency: 500
filter-action: True
critic-l2-reg: 0.0003
gating-layer-size: [32, 32]
epoch-step-num: 5000000
gating-index: None
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-start-size: 10000
n-step: 1
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
render-eval: False
max-path-step: 5000
batch-size: 128
task-weight: 0.0
rollout-step-num: 1
HLC-frequency: 25
loss-output-smooth-coeff: 2.0
test-num: 4
train-step-num: 1
expert-index: None
loss-output-bound-coeff: 0.0
replay-ratio: 1
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
max-path-num: 20
Physics-frequency: 1000
loss-output-diff-coeff: 0
bullet-default-PD: False
max-episode-num: 5000000
reward-scale: 0.1
critic-lr: 0.0003
state-dim: 18
actor-activation-fn: ['relu', 'relu', 'None']
epoch-num: 500
max-step-num: 2500000000
squash-action: True
tau: 0.001
critic-layer-size: [256, 256]
actor-layer-size: [256, 256]
prioritized-exp-replay: True
