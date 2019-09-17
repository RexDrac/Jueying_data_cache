batch-size: 128
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
gating-layer-size: [32, 32]
action-dim: 12
critic-l2-reg: 0.0003
critic-weight-decay: 1e-06
interpolation: False
critic-lr: 0.0003
max-train-time: 10
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
record-start-size: 10000.0
task-weight: 0.0
train-step-num: 1
replay-buffer-size: 1000000
expert-num: 4
HLC-frequency: 25
tau: 0.001
expert-index: None
replay-ratio: 1
imitation-weight: 1.0
actor-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
max-path-num: 20
max-path-step: 5000
loss-entropy-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
LLC-frequency: 500
state-dim: 18
gamma: 0.995
render-eval: False
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
actor-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
actor-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
gating-index: None
filter-torque: False
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
critic-layer-size: [256, 256]
actor-l2-reg: 0.0003
prioritized-exp-replay: True
joint-interpolation: True
loss-output-bound-coeff: 0.0
Physics-frequency: 1000
test-num: 4
actor-weight-decay: 1e-06
loss-output-diff-coeff: 0
max-step-num: 2500000000
epoch-num: 500
epoch-step-num: 5000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
