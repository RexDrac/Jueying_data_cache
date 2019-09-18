task-weight: 0.0
max-train-time: 10
expert-index: None
epoch-step-num: 5000000
reward-scale: 0.1
max-path-num: 20
gating-layer-size: [32, 32]
actor-l2-reg: 0.0003
gating-index: None
joint-interpolation: True
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
train-step-num: 1
max-step-num: 2500000000
loss-output-diff-coeff: 0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
imitation-weight: 1.0
HLC-frequency: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
filter-torque: False
critic-l2-reg: 0.0003
prioritized-exp-replay: True
LLC-frequency: 500
batch-size: 128
test-num: 4
action-dim: 12
max-episode-num: 5000000
loss-output-smooth-coeff: 2.0
max-test-time: 10
record-start-size: 10000.0
filter-action: True
env-id: HumanoidBalanceFilter-v0
loss-entropy-coeff: 0.0
n-step: 1
total-step-num: 2500000000
actor-layer-size: [256, 256]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
rollout-step-num: 1
critic-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
expert-num: 4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.995
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
tau: 0.001
replay-buffer-size: 1000000
max-path-step: 5000
interpolation: False
squash-action: True
state-dim: 18
loss-output-bound-coeff: 0.0
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
render-eval: False
actor-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
critic-layer-size: [256, 256]
Physics-frequency: 1000
