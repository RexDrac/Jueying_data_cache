epoch-num: 500
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
loss-output-smooth-coeff: 1.0
imitation-weight: 1.0
env-id: HumanoidBalanceFilter-v0
actor-lr: 0.0003
gating-index: None
max-path-num: 20
critic-lr: 0.0003
record-start-size: 10000.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-diff-coeff: 0
critic-weight-decay: 1e-06
tau: 0.001
state-dim: 18
expert-num: 4
critic-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
render-eval: False
prioritized-exp-replay: True
gamma: 0.995
task-weight: 0.0
max-step-num: 2500000000
replay-ratio: 1
Physics-frequency: 1000
train-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
expert-index: None
rollout-step-num: 1
HLC-frequency: 25
filter-action: True
actor-weight-decay: 1e-06
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-layer-size: [32, 32]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
test-num: 4
critic-l2-reg: 0.0003
max-train-time: 10
max-episode-num: 5000000
bullet-default-PD: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
batch-size: 128
epoch-step-num: 5000000
actor-l2-reg: 0.0003
filter-torque: False
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
max-path-step: 5000
interpolation: False
replay-buffer-size: 1000000
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
n-step: 1
reward-scale: 0.1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
LLC-frequency: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
