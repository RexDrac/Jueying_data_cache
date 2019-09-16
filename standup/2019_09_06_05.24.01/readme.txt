state-dim: 18
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: None
env-id: HumanoidBalanceFilter-v0
render-eval: False
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
task-weight: 0.0
bullet-default-PD: False
actor-layer-size: [256, 256]
replay-start-size: 10000
max-test-time: 10
replay-buffer-size: 1000000
max-episode-num: 5000000
loss-output-smooth-coeff: 1.0
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
batch-size: 128
action-bounds: [[-0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317
  -0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317 ]
 [ 0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268
   0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268 ]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
rollout-step-num: 1
interpolation: False
gating-layer-size: [32, 32]
critic-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
filter-torque: False
actor-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
critic-layer-size: [256, 256]
reward-scale: 0.1
action-dim: 12
expert-num: 4
n-step: 1
imitation-weight: 1.0
joint-interpolation: True
critic-lr: 0.0003
max-step-num: 2500000000
Physics-frequency: 1000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
LLC-frequency: 500
test-num: 4
actor-l2-reg: 0.0003
max-path-step: 5000
max-path-num: 20
tau: 0.001
loss-entropy-coeff: 0.0
gamma: 0.995
epoch-num: 500
prioritized-exp-replay: True
critic-l2-reg: 0.0003
expert-index: None
record-start-size: 10000.0
epoch-step-num: 5000000
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
replay-ratio: 1
loss-output-diff-coeff: 0
total-step-num: 2500000000
filter-action: True
HLC-frequency: 25
actor-weight-decay: 1e-06
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
