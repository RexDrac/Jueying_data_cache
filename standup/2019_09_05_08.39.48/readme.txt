critic-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
replay-start-size: 10000
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
filter-torque: False
replay-buffer-size: 1000000
total-step-num: 2500000000
actor-weight-decay: 1e-06
max-test-time: 10
epoch-step-num: 5000000
interpolation: False
expert-num: 4
gamma: 0.995
task-weight: 0.0
filter-action: True
action-bounds: [[-0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317
  -0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317 ]
 [ 0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268
   0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268 ]]
env-id: HumanoidBalanceFilter-v0
action-dim: 12
rollout-step-num: 1
critic-weight-decay: 1e-06
loss-entropy-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-lr: 0.0003
Physics-frequency: 1000
record-start-size: 10000.0
n-step: 1
actor-l2-reg: 0.0003
bullet-default-PD: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-index: None
loss-output-diff-coeff: 0
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
gating-layer-size: [32, 32]
batch-size: 128
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
reward-scale: 0.1
replay-ratio: 1
render-eval: False
max-path-step: 5000
HLC-frequency: 25
actor-lr: 0.0003
critic-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
test-num: 4
loss-output-smooth-coeff: 1.0
actor-layer-size: [256, 256]
prioritized-exp-replay: True
joint-interpolation: True
max-train-time: 10
critic-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 42
actor-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 1.0
loss-output-bound-coeff: 0.0
max-step-num: 2500000000
train-step-num: 1
LLC-frequency: 500
squash-action: True
expert-index: None
