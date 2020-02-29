task-weight: 0.0
actor-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
joint-interpolation: True
gamma: 0.995
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
max-step-num: 2500000000
critic-weight-decay: 1e-06
test-num: 4
max-path-step: 5000
imitation-weight: 1.0
gating-index: None
epoch-num: 500
render-eval: False
HLC-frequency: 25
expert-num: 4
critic-layer-size: [256, 256]
actor-l2-reg: 0.0003
loss-output-diff-coeff: 0
squash-action: True
train-step-num: 1
loss-output-smooth-coeff: 2.0
critic-lr: 0.0003
n-step: 1
loss-entropy-coeff: 0.0
max-test-time: 10
prioritized-exp-replay: True
actor-layer-size: [256, 256]
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
filter-torque: False
interpolation: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
replay-ratio: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
reward-scale: 0.1
critic-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
tau: 0.001
max-train-time: 10
loss-output-bound-coeff: 0.0
replay-start-size: 10000
batch-size: 128
gating-layer-size: [32, 32]
env-id: HumanoidBalanceFilter-v0
filter-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
Physics-frequency: 1000
max-path-num: 20
state-dim: 18
action-dim: 12
LLC-frequency: 500
replay-buffer-size: 1000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
actor-lr: 0.0003
total-step-num: 2500000000
