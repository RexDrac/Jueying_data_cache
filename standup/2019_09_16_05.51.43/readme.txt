loss-output-bound-coeff: 0.0
max-train-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-weight-decay: 1e-06
replay-start-size: 10000
gating-layer-size: [32, 32]
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
action-dim: 12
Physics-frequency: 1000
train-step-num: 1
critic-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
LLC-frequency: 500
critic-weight-decay: 1e-06
joint-interpolation: True
epoch-step-num: 5000000
max-step-num: 2500000000
loss-output-smooth-coeff: 2.0
reward-scale: 0.1
expert-num: 4
record-start-size: 10000.0
max-path-num: 20
HLC-frequency: 25
env-id: HumanoidBalanceFilter-v0
total-step-num: 2500000000
state-dim: 18
n-step: 1
actor-lr: 0.0003
max-episode-num: 5000000
task-weight: 0.0
render-eval: False
gamma: 0.995
prioritized-exp-replay: True
max-path-step: 5000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-lr: 0.0003
test-num: 4
squash-action: True
imitation-weight: 1.0
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
interpolation: False
filter-action: True
loss-entropy-coeff: 0.0
gating-index: None
critic-layer-size: [256, 256]
batch-size: 128
epoch-num: 500
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-torque: False
max-test-time: 10
expert-index: None
loss-output-diff-coeff: 0
actor-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
replay-ratio: 1
tau: 0.001
