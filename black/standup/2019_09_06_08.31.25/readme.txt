loss-output-bound-coeff: 0.0
record-start-size: 10000.0
imitation-weight: 1.0
train-step-num: 1
action-bounds: [[-0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317
  -0.52359878 -2.7925268   0.6981317  -0.52359878 -2.7925268   0.6981317 ]
 [ 0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268
   0.52359878  0.34906585  2.7925268   0.52359878  0.34906585  2.7925268 ]]
actor-layer-size: [256, 256]
gamma: 0.995
reward-scale: 0.1
state-dim: 42
critic-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
LLC-frequency: 500
max-episode-num: 5000000
bullet-default-PD: False
prioritized-exp-replay: True
gating-layer-size: [32, 32]
replay-start-size: 10000
loss-entropy-coeff: 0.0
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
interpolation: False
expert-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.0
action-dim: 12
replay-buffer-size: 1000000
max-test-time: 10
replay-ratio: 1
max-path-num: 20
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
loss-output-diff-coeff: 0
critic-weight-decay: 1e-06
n-step: 1
filter-action: True
max-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-step-num: 5000000
env-id: HumanoidBalanceFilter-v0
test-num: 4
total-step-num: 2500000000
expert-index: None
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
Physics-frequency: 1000
batch-size: 128
filter-torque: False
epoch-num: 500
max-train-time: 10
render-eval: False
critic-lr: 0.0003
squash-action: True
actor-lr: 0.0003
gating-index: None
loss-output-smooth-coeff: 1.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
tau: 0.001
max-path-step: 5000
