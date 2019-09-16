joint-interpolation: True
max-path-step: 5000
task-weight: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
epoch-num: 500
replay-buffer-size: 1000000
test-num: 4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-weight-decay: 1e-06
critic-l2-reg: 0.0003
epoch-step-num: 5000000
total-step-num: 2500000000
max-test-time: 10
reward-scale: 0.1
max-path-num: 20
record-start-size: 10000.0
interpolation: False
prioritized-exp-replay: True
actor-lr: 0.0003
batch-size: 128
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-layer-size: [32, 32]
action-dim: 12
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
expert-index: None
squash-action: True
render-eval: False
max-episode-num: 5000000
imitation-weight: 1.0
tau: 0.001
critic-lr: 0.0003
filter-action: True
env-id: HumanoidBalanceFilter-v0
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.995
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
LLC-frequency: 500
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-index: None
actor-l2-reg: 0.0003
Physics-frequency: 1000
n-step: 1
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
bullet-default-PD: False
actor-layer-size: [256, 256]
expert-num: 4
max-step-num: 2500000000
replay-start-size: 10000
max-train-time: 10
replay-ratio: 1
filter-torque: False
state-dim: 18
loss-output-diff-coeff: 0
