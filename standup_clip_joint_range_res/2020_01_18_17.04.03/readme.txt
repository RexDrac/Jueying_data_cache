render-eval: False
loss-output-diff-coeff: 0
max-train-time: 10
critic-lr: 0.0003
prioritized-exp-replay: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-l2-reg: 0.0003
train-step-num: 1
env-id: HumanoidBalanceFilter-v0
max-path-num: 20
epoch-num: 500
HLC-frequency: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
imitation-weight: 1.0
n-step: 1
max-test-time: 10
max-path-step: 5000
loss-output-smooth-coeff: 2.0
gating-index: None
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
replay-ratio: 1
joint-interpolation: True
total-step-num: 2500000000
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
gamma: 0.995
max-episode-num: 5000000
replay-start-size: 10000
rollout-step-num: 1
batch-size: 128
record-start-size: 10000.0
expert-index: None
actor-l2-reg: 0.0003
actor-lr: 0.0003
critic-weight-decay: 1e-06
critic-layer-size: [256, 256]
state-dim: 18
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
replay-buffer-size: 1000000
Physics-frequency: 1000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
action-dim: 12
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-layer-size: [32, 32]
LLC-frequency: 500
interpolation: False
expert-num: 4
tau: 0.001
filter-action: True
actor-layer-size: [256, 256]
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
actor-weight-decay: 1e-06
max-step-num: 2500000000
task-weight: 0.0
loss-output-bound-coeff: 0.0
