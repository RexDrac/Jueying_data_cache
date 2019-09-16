render-eval: False
replay-buffer-size: 1000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
imitation-weight: 1.0
reward-scale: 0.1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
replay-start-size: 10000
gamma: 0.995
state-dim: 42
actor-lr: 0.0003
filter-action: True
actor-l2-reg: 0.0003
epoch-num: 500
max-path-num: 20
LLC-frequency: 500
loss-output-diff-coeff: 0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
max-episode-num: 5000000
test-num: 4
actor-layer-size: [256, 256]
loss-output-smooth-coeff: 1.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-layer-size: [32, 32]
batch-size: 128
max-train-time: 10
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
max-path-step: 5000
critic-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
rollout-step-num: 1
action-bounds: [[-0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317
  -0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317 ]
 [ 0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268
   0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268 ]]
prioritized-exp-replay: True
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
gating-index: None
joint-interpolation: True
interpolation: False
action-dim: 12
actor-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
HLC-frequency: 25
record-start-size: 10000.0
total-step-num: 2500000000
task-weight: 0.0
expert-num: 4
max-step-num: 2500000000
expert-index: None
critic-weight-decay: 1e-06
max-test-time: 10
squash-action: True
filter-torque: False
epoch-step-num: 5000000
bullet-default-PD: False
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
critic-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
