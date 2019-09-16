rollout-step-num: 1
critic-weight-decay: 1e-06
prioritized-exp-replay: True
gamma: 0.955
train-step-num: 1
LLC-frequency: 500
filter-torque: False
gating-index: None
epoch-num: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
dsr-gait-freq: 1.667
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
filter-action: True
replay-start-size: 10000
actor-lr: 0.0003
dsr-gait-period: 0.6
replay-buffer-size: 1000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-layer-size: [256, 256]
max-episode-num: 5000000
test-num: 4
loss-output-smooth-coeff: 1.0
env-id: HumanoidBalanceFilter-v0
squash-action: True
epoch-step-num: 5000000
max-path-step: 5000
joint-interpolation: True
HLC-frequency: 25
task-weight: 0.5
total-step-num: 2500000000
Physics-frequency: 1000
loss-output-diff-coeff: 0
batch-size: 128
interpolation: False
tau: 0.001
action-dim: 12
state-dim: 25
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
actor-weight-decay: 1e-06
loss-output-bound-coeff: 0.0
imitation-weight: 0.5
expert-num: 4
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
reward-scale: 0.1
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
gating-layer-size: [32, 32]
replay-ratio: 1
actor-l2-reg: 0.0003
max-path-num: 20
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
render-eval: False
max-test-time: 10
critic-lr: 0.0003
record-start-size: 10000.0
