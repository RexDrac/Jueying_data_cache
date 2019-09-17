filter-action: True
prioritized-exp-replay: True
total-step-num: 2500000000
task-weight: 0.5
loss-output-bound-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-period: 0.6
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-torque: False
actor-weight-decay: 1e-06
expert-index: None
record-start-size: 10000.0
max-episode-num: 5000000
rollout-step-num: 1
actor-lr: 0.0003
replay-start-size: 10000
epoch-step-num: 5000000
max-path-num: 20
squash-action: True
loss-output-smooth-coeff: 0.5
gamma: 0.955
n-step: 1
epoch-num: 500
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
critic-weight-decay: 1e-06
replay-buffer-size: 1000000
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
max-step-num: 2500000000
critic-l2-reg: 0.0003
Physics-frequency: 1000
test-num: 4
imitation-weight: 0.5
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [32, 32]
max-train-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
render-eval: False
gating-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-test-time: 10
max-path-step: 5000
LLC-frequency: 500
actor-l2-reg: 0.0003
critic-layer-size: [256, 256]
gating-index: None
actor-layer-size: [256, 256]
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
batch-size: 128
replay-ratio: 1
critic-activation-fn: ['relu', 'relu', 'None']
state-dim: 23
action-dim: 12
dsr-gait-freq: 1.667
bullet-default-PD: False
expert-num: 4
interpolation: False
