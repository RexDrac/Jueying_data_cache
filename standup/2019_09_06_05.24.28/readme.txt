record-start-size: 10000.0
expert-num: 4
max-path-num: 20
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
epoch-step-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
interpolation: False
task-weight: 0.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
replay-buffer-size: 1000000
gating-index: None
critic-weight-decay: 1e-06
prioritized-exp-replay: True
max-step-num: 2500000000
render-eval: False
squash-action: True
epoch-num: 500
critic-lr: 0.0003
filter-torque: False
action-dim: 12
state-dim: 18
reward-scale: 0.1
actor-weight-decay: 1e-06
replay-ratio: 1
train-step-num: 1
actor-l2-reg: 0.0003
replay-start-size: 10000
bullet-default-PD: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
max-test-time: 10
imitation-weight: 1.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
joint-interpolation: True
env-id: HumanoidBalanceFilter-v0
critic-layer-size: [256, 256]
HLC-frequency: 25
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
LLC-frequency: 500
n-step: 1
max-episode-num: 5000000
actor-lr: 0.0003
total-step-num: 2500000000
max-train-time: 10
loss-output-bound-coeff: 0.0
loss-output-diff-coeff: 0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317
  -0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317 ]
 [ 0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268
   0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268 ]]
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
rollout-step-num: 1
gating-layer-size: [32, 32]
critic-l2-reg: 0.0003
batch-size: 128
gamma: 0.995
expert-index: None
actor-layer-size: [256, 256]
