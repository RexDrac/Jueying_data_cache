normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
env-id: HumanoidBalanceFilter-v0
LLC-frequency: 500
reward-scale: 0.1
critic-l2-reg: 0.0003
train-step-num: 1
filter-torque: False
actor-weight-decay: 1e-06
loss-entropy-coeff: 0.0
bullet-default-PD: False
gating-layer-size: [32, 32]
action-dim: 12
loss-output-smooth-coeff: 2.0
joint-interpolation: True
max-path-step: 5000
critic-weight-decay: 1e-06
task-weight: 0.5
state-dim: 23
replay-ratio: 1
gating-index: None
record-start-size: 10000.0
critic-layer-size: [256, 256]
actor-lr: 0.0003
max-path-num: 20
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
prioritized-exp-replay: True
expert-num: 4
render-eval: False
loss-output-bound-coeff: 0.0
max-step-num: 2500000000
HLC-frequency: 25
interpolation: False
Physics-frequency: 1000
rollout-step-num: 1
max-train-time: 10
actor-l2-reg: 0.0003
test-num: 4
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
epoch-step-num: 5000000
gamma: 0.955
filter-action: True
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-bounds: [[-0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512
  -0.38397244 -2.75762022  0.66322512 -0.38397244 -2.75762022  0.66322512]
 [ 0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668
   0.38397244  0.48869219  2.84488668  0.38397244  0.48869219  2.84488668]]
replay-buffer-size: 1000000
loss-output-diff-coeff: 0
max-episode-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.5
expert-index: None
replay-start-size: 10000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
total-step-num: 2500000000
dsr-gait-period: 0.6
actor-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
epoch-num: 500
max-test-time: 10
tau: 0.001
dsr-gait-freq: 1.667
