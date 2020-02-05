epoch-step-num: 5000000
gamma: 0.995
loss-output-bound-coeff: 0.0
tau: 0.001
max-test-time: 10
actor-lr: 0.0003
critic-l2-reg: 0.0003
max-path-num: 20
loss-entropy-coeff: 0.0
render-eval: False
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-dim: 12
max-step-num: 2500000000
critic-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
imitation-weight: 1.0
loss-output-diff-coeff: 0
HLC-frequency: 25
train-step-num: 1
bullet-default-PD: False
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
actor-layer-size: [256, 256]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
state-dim: 18
n-step: 1
critic-lr: 0.0003
LLC-frequency: 500
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
joint-interpolation: True
Physics-frequency: 1000
expert-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
gating-index: None
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
task-weight: 0.0
max-episode-num: 5000000
max-train-time: 10
replay-ratio: 1
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
test-num: 4
gating-layer-size: [32, 32]
expert-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
prioritized-exp-replay: True
record-start-size: 10000.0
max-path-step: 5000
total-step-num: 2500000000
rollout-step-num: 1
loss-output-smooth-coeff: 2.0
filter-torque: False
reward-scale: 0.1
batch-size: 128
critic-weight-decay: 1e-06
epoch-num: 500
interpolation: False
