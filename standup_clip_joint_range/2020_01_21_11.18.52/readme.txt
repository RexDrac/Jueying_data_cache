critic-layer-size: [256, 256]
squash-action: True
total-step-num: 2500000000
prioritized-exp-replay: True
tau: 0.001
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
critic-l2-reg: 0.0003
actor-weight-decay: 1e-06
train-step-num: 1
batch-size: 128
epoch-step-num: 5000000
state-dim: 18
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-start-size: 10000
max-train-time: 10
gamma: 0.995
max-path-step: 5000
Physics-frequency: 1000
max-episode-num: 5000000
filter-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
filter-torque: False
epoch-num: 500
action-dim: 12
reward-scale: 0.1
bullet-default-PD: False
gating-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
loss-output-bound-coeff: 0.0
gating-layer-size: [32, 32]
loss-output-diff-coeff: 0
max-path-num: 20
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-l2-reg: 0.0003
expert-num: 4
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
actor-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 1.0
max-step-num: 2500000000
task-weight: 0.0
n-step: 1
render-eval: False
HLC-frequency: 25
critic-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
replay-ratio: 1
gating-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
interpolation: False
expert-index: None
critic-lr: 0.0003
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
test-num: 4
joint-interpolation: True
replay-buffer-size: 1000000
rollout-step-num: 1
loss-output-smooth-coeff: 2.0
critic-weight-decay: 1e-06
