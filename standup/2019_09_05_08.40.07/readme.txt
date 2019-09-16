actor-lr: 0.0003
max-episode-num: 5000000
tau: 0.001
prioritized-exp-replay: True
critic-l2-reg: 0.0003
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
filter-torque: False
imitation-weight: 1.0
test-num: 4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 42
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
reward-scale: 0.1
replay-buffer-size: 1000000
loss-output-bound-coeff: 0.0
critic-layer-size: [256, 256]
max-path-num: 20
gating-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
max-test-time: 10
replay-ratio: 1
record-start-size: 10000.0
train-step-num: 1
epoch-num: 500
gating-index: None
render-eval: False
gating-layer-size: [32, 32]
max-path-step: 5000
expert-num: 4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
n-step: 1
squash-action: True
actor-l2-reg: 0.0003
interpolation: False
filter-action: True
max-train-time: 10
action-dim: 12
loss-entropy-coeff: 0.0
action-bounds: [[-0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317
  -0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317 ]
 [ 0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268
   0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268 ]]
total-step-num: 2500000000
max-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
actor-weight-decay: 1e-06
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-index: None
loss-output-diff-coeff: 0
replay-start-size: 10000
critic-lr: 0.0003
epoch-step-num: 5000000
loss-output-smooth-coeff: 1.0
batch-size: 128
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
joint-interpolation: True
gamma: 0.995
task-weight: 0.0
